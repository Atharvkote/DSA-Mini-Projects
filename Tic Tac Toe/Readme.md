# Tic-Tac-Toe Game

## Overview

This is a simple command-line Tic-Tac-Toe game implemented in Java. Two players, 'X' and 'O', take turns to place their marks on a 3x3 board. The game continues until one player wins or the board is full.

## Features

- Two-player game ('X' and 'O')
- Detects a win for rows, columns, and diagonals
- Handles invalid moves

## How to Run

1. **Clone the repository** (if applicable) or copy the code into your local development environment.

2. **Compile the Java program**:
    ```bash
    javac Main.java
    ```

3. **Run the program**:
    ```bash
    java Main
    ```

## Game Instructions

1. The game will display an empty 3x3 board.
2. Players will be prompted to enter their moves by specifying the row and column numbers.
3. The board will be updated after each valid move, and the current state will be printed.
4. The game will continue until a player wins or there are no empty cells left.

## Example Visualization

```
   |   |   
---------
   |   |   
---------
   |   |   

Player X enter: 0 0
 
 X |   |   
---------
   |   |   
---------
   |   |   

Player O enter: 1 1

 X |   |   
---------
   | O |   
---------
   |   |   

Player X enter: 0 1

 X | X |   
---------
   | O |   
---------
   |   |   
```

The game board is displayed after each move. Players enter their moves in the format `row col`, where both `row` and `col` are integers ranging from 0 to 2.

## Code Breakdown

- **Main Class**: Contains the main game loop and player input handling.
- **printBoard Method**: Prints the current state of the board.
- **haveWon Method**: Checks if the current player has won by examining rows, columns, and diagonals.

## Future Enhancements

- Add detection for a tie when the board is full and no player has won.
- Improve input handling to check for out-of-bounds indices.
- Create a graphical user interface (GUI) for better 
