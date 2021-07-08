# Two Player Tic-Tac-Toe Game in C

###The main source code file :
-tictactoeC.c 

###Executable file for the project:
-tictactoeC.exe

##About The Game
 - This is a two player tic tac toe game ( meaning both the players are human ).
 - The first player to place 3 of their mark forming a straight line wins.

##Usage
Alternates between Player1 and Player2. Enter a digit [1-9] to move:

    1 | 2 | 3
    ---------
    4 | 5 | 6
    ---------
    7 | 8 | 9
    
 The game ends if:
- A player completes three in a row; that player wins
- All squares are taken; neither player wins
- A player makes an illegal move; their opponent wins
   

## Challenges Faced and How Was It Overcome
| No. | Challenge | Solution
|-----|-----------|--------
|1. | Output was not matching the expectation | Modified the logic of the program and code itself 
|2. | Game suddenly gets exited in the middle | Modified a segment of the code and eliminated the usage of conio.h |
|3. | Error while Building the makefile | Trial and Error and referred Mini Project Template
