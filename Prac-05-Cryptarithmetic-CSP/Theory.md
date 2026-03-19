Theory – Cryptarithmetic Puzzle using CSP

Constraint Satisfaction Problem (CSP):
A CSP is a problem where the goal is to find values for variables such that all constraints are satisfied.

Components of CSP:
• Variables – Letters in the puzzle (S, E, N, D, M, O, R, Y)  
• Domains – Digits from 0 to 9  
• Constraints – Rules such as unique values and valid arithmetic  

Cryptarithmetic Problem:
Cryptarithmetic is a type of puzzle where digits are replaced by alphabets.

Example:
SEND + MORE = MONEY

Rules:
• Each letter represents a unique digit  
• No two letters can have the same digit  
• Leading digits cannot be zero  
• The equation must be mathematically correct  

Approach Used:
• Extract all unique letters  
• Generate permutations of digits  
• Apply constraints  
• Evaluate equation  
• Stop when valid solution is found  

Algorithm:
1. Take input puzzle  
2. Extract unique letters  
3. Generate all possible digit permutations  
4. Check constraints (no leading zero, unique digits)  
5. Replace letters with digits  
6. Evaluate equation  
7. Print solution if valid  

Advantages:
• Simple and effective approach  
• Demonstrates CSP clearly  

Disadvantages:
• Time consuming for large problems  
• Uses brute-force method  
