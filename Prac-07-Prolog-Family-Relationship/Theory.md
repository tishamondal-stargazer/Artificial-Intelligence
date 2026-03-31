Theory – Prolog Family Relationship

Prolog (Programming in Logic)  
Prolog is a declarative programming language used in Artificial Intelligence based on First-Order Predicate Logic.

Key Concepts  

Facts  
Basic statements about relationships  
Example: parent(john, mary)

Rules  
Define relationships using logic  
Example: father(X, Y) :- parent(X, Y), male(X)

Unification  
Matching variables with values  
Example: parent(john, X) → X = mary

Backtracking  
Prolog automatically searches for all possible solutions

Family Relationship Model  

This program represents relationships like:
• Parent  
• Father  
• Mother  
• Sibling  
• Grandparent  
• Ancestor  

Recursion  

Used in ancestor rule to find indirect relationships

Example:  
ancestor(X, Y) :- parent(X, Y)  
ancestor(X, Y) :- parent(X, Z), ancestor(Z, Y)

Advantages  
• Simple knowledge representation  
• Automatic search using backtracking  
• Powerful for AI logic problems  

Applications  
• Expert systems  
• Natural language processing  
• Knowledge-based systems  
