Practical 07 – Prolog Family Relationship

Aim  
Write a Prolog Program to demonstrate the concept of Family Relationship.

Description  
This practical demonstrates knowledge representation using Prolog, a logic programming language used in Artificial Intelligence.

The program models family relationships using facts and rules. It shows how logical inference, unification, and backtracking work in Prolog.

The system defines relationships such as:
• Father  
• Mother  
• Sibling  
• Grandparent  
• Ancestor  

Prolog uses:
• Facts → Basic information  
• Rules → Logical relationships  
• Queries → Questions to get results  

Tools Used  
SWI-Prolog  
Command Prompt / Terminal  

How to Run the Program  

1. Install SWI-Prolog  
2. Open terminal  
3. Run:
   swipl  
4. Load file:
   ?- consult('family.pl').  
   OR  
   ?- [family].  

5. Run queries like:
   ?- father(john, sam).  
   ?- sibling(sam, anna).  

Sample Output  

true.  
X = mary  
