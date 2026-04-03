Theory – Semantic Network

Semantic Network  
A semantic network is a graphical representation of knowledge where:

• Nodes represent objects or concepts  
• Edges represent relationships  

Types of Relationships  

ISA Relationship  
Represents inheritance  
Example: isa(dog, animal)

HAS-A Relationship  
Represents properties  
Example: has(dog, tail)

CAN Relationship  
Represents ability  
Example: can(bird, fly)

Predicate Logic Representation  

isa(dog, animal)  
has(dog, tail)  
can(bird, fly)  

Inheritance Rule  

If isa(X, Y) and has(Y, Z)  
Then has(X, Z)

Working of Program  

• Relations stored as tuples  
• Uses stack for inference  
• Follows ISA chain  
• Returns CAN properties  

Advantages  

• Easy to understand  
• Supports inheritance  
• Good for knowledge representation  

Applications  

• Expert systems  
• NLP  
• Knowledge graphs  
