# Practical 03 – Tic Tac Toe Game with AI Player

## Aim
To build a Tic-Tac-Toe game engine in Python where a human player can play against the computer.

## Objective
• To understand the concept of the Tic-Tac-Toe game.  
• To develop problem solving ability using Artificial Intelligence concepts.  
• To implement a simple game engine using Python.

## Description
Tic-Tac-Toe is a popular two-player game played on a 3x3 grid. The players take turns marking spaces on the board with their respective symbols, usually X and O. The objective of the game is to place three of the same symbols in a horizontal, vertical, or diagonal row.

In this practical, a Tic-Tac-Toe game is implemented using Python. The program allows players to make moves by selecting positions on the board. The game engine continuously checks for winning conditions or draw situations after every move.

The board is represented as a list containing nine positions corresponding to the cells of the grid. The game alternates turns between players until a winning condition is achieved or the board becomes full.

This practical demonstrates how basic Artificial Intelligence concepts and game logic can be applied to develop simple interactive games.

## How to Run the Program

1. Install Python on your system.

2. Clone or download the repository.

3. Navigate to the folder:

Artificial-Intelligence/Prac-03-Tic-Tac-Toe-AI

4. Run the Python program:

python ai_Prac3.py

5. Enter the position (1–9) when prompted to place your mark on the board.

## Sample Output

 |   |  
---+---+---
 |   |  
---+---+---
 |   |  

Player X, choose a position (1-9): 1

 X |   |  
---+---+---
   |   |  
---+---+---
   |   |  

Player O, choose a position (1-9): 5

 X |   |  
---+---+---
   | O |  
---+---+---
   |   |  

Player X, choose a position (1-9): 2  
Player O, choose a position (1-9): 9  
Player X, choose a position (1-9): 3  

🎉 Player X wins!
