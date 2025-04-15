# Tic-Tac-Toe
Basic Python Project

A simple, text-based implementation of the classic Tic-Tac-Toe board game for two players, written in Python. 

This is a console-based, two-player game of Tic-Tac-Toe, where players take turns entering their moves by choosing a space number from 1 to 9 on a 3×3 grid.

Board layout:

 1 | 2 | 3
 
---+---+---

 4 | 5 | 6
 
---+---+---

 7 | 8 | 9
 
How to Play

The game starts by displaying an empty board.

Player X goes first, followed by Player O.

Players take turns choosing a number between 1-9 corresponding to the space they want to mark.

The game checks for:

A win (three of the same marks in a row, column, or diagonal)

A tie (all spaces filled with no winner)

After the game ends, a winner or tie is announced.

Code Structure

main() – Game loop and player turn management

getBlankBoard() – Creates a blank game board

getBoardStr() – Returns a string representation of the board

isValidSpace() – Checks if a move is valid

isWinner() – Checks if a player has won

isBoardFull() – Checks for a full board (tie)

updateBoard() – Updates the board with a player's move

