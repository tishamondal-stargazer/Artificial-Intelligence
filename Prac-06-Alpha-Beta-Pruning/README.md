Practical 06 – Alpha Beta Pruning in Game Development

Aim  
Implement the concept of Alpha Beta Pruning for optimization in game development.

Description  
This practical demonstrates the implementation of Alpha–Beta Pruning, an optimization technique used with the Minimax algorithm in Artificial Intelligence. It is widely used in two-player turn-based games such as Tic-Tac-Toe, Chess, and Checkers.

The objective is to reduce the number of nodes evaluated in the game tree, thereby improving performance and enabling faster decision-making.

In this implementation, a Tic-Tac-Toe game is used where:
• The human player plays as 'X'  
• The AI plays as 'O'  
• The AI uses Alpha-Beta Pruning to choose optimal moves  

The algorithm eliminates unnecessary branches using alpha (α) and beta (β) values:
• Alpha → Best value for maximizer  
• Beta → Best value for minimizer  
• Pruning occurs when α ≥ β  

This ensures the same optimal result as Minimax but with improved efficiency.

Tools Used  
Python  
VS Code  
Command Prompt / Terminal  

How to Run the Program  

1. Open the folder in VS Code  
2. Open terminal  
3. Run the command:

python ai_Prac6.py

4. Enter row and column values (1–3)

Sample Output  

X |   |  
---------  
  | O |  
---------  
  |   |  

AI: 2 2  

X Wins! / O Wins! / It's a Tie!
