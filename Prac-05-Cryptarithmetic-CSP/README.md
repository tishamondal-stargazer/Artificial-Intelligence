Practical 05 – Cryptarithmetic Puzzle using CSP

Aim
Write a code to implement Cryptarithmetic puzzle (SEND + MORE = MONEY) using the concept of Constraint Satisfaction Problem (CSP).

Description
This practical demonstrates the implementation of a Cryptarithmetic puzzle using Python based on the concept of Constraint Satisfaction Problem (CSP). In this type of problem, each alphabet represents a unique digit from 0 to 9, and the goal is to find a valid mapping such that the arithmetic equation holds true.

The puzzle SEND + MORE = MONEY is solved by assigning digits to letters while satisfying the following constraints:

Each letter must have a unique digit  
Leading letters cannot be assigned zero  
The final arithmetic equation must be correct  

The program uses permutations to generate all possible combinations of digits and applies constraints to filter valid solutions. Once a valid mapping is found, the corresponding numerical equation is displayed.

This practical highlights how CSP techniques such as variable assignment, domain constraints, and backtracking can be applied to solve logical puzzles efficiently.

Tools Used
Python  
VS Code  
Command Prompt / Terminal  

How to Run the Program
Open the folder in VS Code.  
Open terminal.  
Run the command:  

python ai_Prac5.py  

Enter the puzzle when prompted.  

Sample Input
SEND + MORE = MONEY  

Sample Output
Solution Found:  
9567 + 1085 == 10652  
Mapping: {'S': 9, 'E': 5, 'N': 6, 'D': 7, 'M': 1, 'O': 0, 'R': 8, 'Y': 2}
