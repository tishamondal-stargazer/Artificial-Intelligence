# Practical 02 – Water Jug Problem

## Aim
To apply the concept of production rules to solve the Water Jug Problem using Artificial Intelligence techniques.

## Description
The Water Jug Problem is a classical Artificial Intelligence puzzle that demonstrates problem solving using state space representation and production rules.

In this problem two jugs of different capacities are given without any measuring marks. The objective is to obtain a specific amount of water using only the allowed operations such as filling, emptying and pouring water between jugs.

In this practical:

Jug X = 4 gallon jug  
Jug Y = 3 gallon jug  

The goal is to obtain exactly 2 gallons of water in the 4-gallon jug.

The program uses Breadth First Search (BFS) to explore possible states and find the correct sequence of actions that leads to the goal state.

The state of the system is represented as:

(x , y)

Where  
x → amount of water in 4 gallon jug  
y → amount of water in 3 gallon jug

The algorithm explores possible transitions until the goal state is achieved.

## How to Run the Program

1. Install Python on your system.

2. Clone or download this repository.

3. Navigate to the folder:

Artificial-Intelligence/Prac-02-Water-Jug-Problem

4. Run the program using the command:

python ai_Prac2.py

5. Enter the required inputs when prompted.

Example:

Enter Jug 1 Size: 4  
Enter Jug 2 Size: 3  
Enter Target Jug Size: 2

## Sample Output

Steps to reach goal:

State (0, 0) -> Action: Fill Jug Y  
State (0, 3) -> Action: Pour Y -> X  
State (3, 0) -> Action: Fill Jug Y  
State (3, 3) -> Action: Pour Y -> X  

Final State: (4, 2)
