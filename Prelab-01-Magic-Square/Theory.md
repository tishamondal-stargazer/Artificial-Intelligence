# Magic Square – Theory

A Magic Square is a square arrangement of numbers in which the sum of the numbers in every row, every column, and both main diagonals is the same. This common value is known as the **Magic Constant** or **Magic Sum**. Magic squares are classical mathematical structures that have been studied for centuries due to their interesting numerical patterns and symmetrical properties.

A normal magic square of order **n** contains the integers from **1 to n²** arranged in an **n × n matrix**. Each number appears exactly once, and the placement of the numbers ensures that the sum of all rows, columns, and diagonals remains constant.

The value of the magic constant depends only on the order of the square and is calculated using the formula:

**M = n(n² + 1) / 2**

For example:

| Order (n) | Magic Constant |
|-----------|---------------|
| 3 | 15 |
| 4 | 34 |
| 5 | 65 |
| 6 | 111 |
| 7 | 175 |

Magic squares are often categorized into different types based on their order:

• **Odd Order Magic Squares** – where n is an odd number (3, 5, 7, etc.).  
• **Doubly Even Magic Squares** – where n is divisible by 4 (4, 8, 12, etc.).  
• **Singly Even Magic Squares** – where n is even but not divisible by 4 (6, 10, 14, etc.).

Among these, odd-order magic squares are the easiest to construct and are commonly generated using a systematic technique known as the **Siamese Method**. This method places numbers sequentially in the matrix according to specific movement rules that ensure the magic constant property is maintained.

In the Siamese method, the first number is placed in a predefined position and each subsequent number is placed by moving diagonally upward and to the right. If the movement goes outside the boundaries of the square, it wraps around to the opposite side. If the target position is already occupied, a different adjustment rule is applied to determine the next valid position.

Magic squares have historical significance and have appeared in various cultures, including ancient Chinese, Indian, and Arabic mathematics. They are also studied in number theory, combinatorics, and recreational mathematics. Apart from their mathematical importance, magic squares are frequently used as puzzles that help develop logical reasoning, pattern recognition, and algorithmic thinking.

In this practical, the concept of magic squares is implemented using a Python program that constructs a magic square for an odd order input. The program demonstrates how mathematical rules can be translated into an algorithm to systematically generate a valid magic square while maintaining the required magic constant.
