Practical 05

Aim:
To implement Cryptarithmetic puzzle (SEND + MORE = MONEY) using Constraint Satisfaction Problem (CSP) approach.

Objective:
• Understand the concept of constraint satisfaction problems  
• Learn how variables, domains and constraints work together  
• Develop problem solving ability using backtracking technique  
• Implement cryptarithmetic puzzle using Python  

Description:
This practical focuses on solving a Cryptarithmetic puzzle using the concept of Constraint Satisfaction Problem (CSP). In this type of problem, digits are replaced by alphabets and the goal is to find a valid mapping such that the arithmetic equation holds true.

The puzzle SEND + MORE = MONEY is used, where each letter represents a unique digit from 0 to 9. The constraints include:
• Each letter must map to a unique digit  
• Leading digits cannot be zero  
• The arithmetic equation must be valid  

The solution is obtained using a brute-force approach with permutations combined with constraint checking. All possible mappings of digits to letters are generated and validated against the given conditions.

The notebook/code includes:
• Taking user input for the puzzle  
• Extracting unique characters  
• Generating permutations of digits  
• Applying constraints such as uniqueness and non-zero leading digits  
• Evaluating the equation  
• Displaying valid solution and mapping  

This practical demonstrates how CSP techniques can be applied to solve logical puzzles efficiently using Python.

Tools Used:
Python  
VS Code  
