# Theory – Water Jug Problem

The Water Jug Problem is a well known puzzle in Artificial Intelligence that is used to demonstrate how problems can be solved using production rules and state space search techniques.

In this problem two jugs of fixed capacities are given. The jugs do not have any markings on them and only a limited set of operations are allowed. The aim is to measure an exact quantity of water using these jugs.

The possible actions include:

• Filling a jug completely from a water source  
• Emptying a jug onto the ground  
• Pouring water from one jug to another until the first jug becomes empty or the second jug becomes full  

The state of the problem is represented as:

(x , y)

Where  
x = amount of water in the first jug  
y = amount of water in the second jug

The solution to the problem is obtained by applying production rules that transform the current state into a new state until the goal state is reached.

The Water Jug Problem is commonly solved using techniques such as:

• Breadth First Search (BFS)  
• Depth First Search (DFS)  
• Recursion with memoization  

These techniques explore different possible states until the required target amount of water is obtained.
