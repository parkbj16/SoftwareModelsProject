# SoftwareModelsProject
## Game description
__Purpose and essence__<br>
Both players want to make 4 in a row of their marker type on the board. The way to play is to choose which way the pieces fall (like the game 2048), but the objective is to get 4 in a row (like the game Connect 4)

__Game Loop__<br>
```
1. GameController places marker randomly (A/B, which alternate every iteration) on the grid (8x8).
2. GameController displays current board.
3. Player (1/2 alternate) picks gravity direction (UP, DOWN, LEFT, RIGHT).
4. GameController shifts all markers in gravity direction.
5. Check:
    if (4 in a row):
        Player (1/2) wins
    else if (board is full):
        Tie
    else:
        Loop to step 1
```
__Input__: UP - DOWN - LEFT - RIGHT
Format: String - has to be one of the 4 words above

__Output__: The board and the message
The message could say "be pick another direction" or show the outcome ("player <1/2> wins" or "tie")
The board is a grid represented by characters in the console that shows where the markers are.

## To do list
- [x] created the github project 
- [ ] submit description
- [ ] submit UML
- [ ] submit use case diagram
