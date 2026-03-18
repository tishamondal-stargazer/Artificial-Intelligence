# Practical 04 – A* Search Algorithm

## Aim

Make use of A* Algorithm to find the goal state (shortest path cost) in the given graph. Also understand how heuristic based search improves efficiency compared to uninformed search methods such as Breadth First Search.

## Description

This practical demonstrates the implementation of the A* Search Algorithm using Python. A* is one of the most efficient search algorithms used in Artificial Intelligence for path finding and graph traversal.

The algorithm combines the advantages of Uniform Cost Search and Greedy Best First Search by using the evaluation function:

f(n) = g(n) + h(n)

Where:

* g(n) = cost from start node to current node
* h(n) = heuristic estimate from current node to goal node
* f(n) = estimated total cost of the solution path

The algorithm always selects the node with the smallest f(n) value and expands it until the goal node is reached.

In this practical, a graph with weighted edges is used. The program takes the start node and goal node as input and determines the optimal path along with the total cost using the A* algorithm.

## Tools Used

Python
VS Code
Command Prompt / Terminal

## How to Run the Program

1. Open the folder in VS Code.
2. Open terminal.
3. Run the command:

python ai_Prac4.py

4. Enter the start node and goal node when prompted.

## Sample Input

Enter start node (A-G): A
Enter goal node (A-G): G

## Sample Output

SUCCESS!! Path found.
Path: A -> C -> E -> G
Total Cost: 7
