
# Tic-Tac-Toe 

## Project Description

This project is a simple implementation of the classic **Tic-Tac-Toe** game, developed using C++. It is a two-player game where players alternate turns to mark spaces in a 3x3 grid with either an 'X' or 'O'. The objective is to get three of your marks in a row, column, or diagonal before your opponent.

## Table of Contents
- [Features](#features)
- [How to Play](#how-to-play)
- [Running the Game](#running-the-game)
- [Code Structure](#code-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- 
## Features

- Two-player mode where players take turns.
- Input validation to ensure players can only mark unoccupied spaces.
- Detects game-over conditions (win or draw).
- Displays the current state of the game board after every move.
- Simple command-line interface.

## How to Play

1. The game is played on a 3x3 grid.
2. Player 1 uses 'X' and Player 2 uses 'O'.
3. Players take turns to choose a cell (1-9) on the grid to place their mark.
4. The first player to get three marks in a row (horizontally, vertically, or diagonally) wins the game.
5. If all 9 cells are filled and no player has three in a row, the game ends in a draw.


## Running the Game

Once the game starts:

- You will be prompted to enter the number corresponding to the cell you want to mark (1-9).
- After each move, the game will display the updated board and check for a winner or draw.
- The game continues until there is a winner or all spaces are filled.

### Example:
```
 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9

Player 1 (X), choose a position: 5

   |   |  
-----------
   | X |  
-----------
   |   |  
```

## Code Structure

The main components of the program are:

- **Game Board**: A 3x3 grid represented by an array.
- **Player Input**: The game takes input from players and ensures that the move is valid.
- **Game Logic**: Includes the rules for determining a win or a draw and switching between players.

## Future Enhancements

Potential improvements and features for future versions:

- **Single-player mode**: Add an AI opponent using basic decision-making (e.g., minimax algorithm).
- **Graphical User Interface (GUI)**: Replace the command-line interface with a graphical one using libraries like SFML or Qt.
- **Improved Input Validation**: Handle incorrect or invalid inputs more gracefully.
- **Game Replay Option**: Allow players to replay the game without restarting the program.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
