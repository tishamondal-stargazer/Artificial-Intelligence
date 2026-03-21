Theory – Alpha Beta Pruning

Minimax Algorithm  
Minimax is a decision-making algorithm used in two-player games. One player tries to maximize the score while the other tries to minimize it.

Problem with Minimax  
It explores all possible game states → very slow for large trees.

Alpha-Beta Pruning  
Alpha-Beta Pruning improves Minimax by eliminating unnecessary nodes.

Alpha (α): Best value that maximizer can achieve  
Beta (β): Best value that minimizer can achieve  

Pruning Condition:  
If α ≥ β → Stop exploring that branch

Working:  
• Max node updates alpha  
• Min node updates beta  
• When condition is met → prune branch  

Algorithm Steps:  
1. Start from root node  
2. Initialize α = -∞, β = +∞  
3. Apply Minimax recursively  
4. Update α and β  
5. Prune when α ≥ β  
6. Return best move  

Advantages:  
• Faster than Minimax  
• Reduces computation  
• Same optimal result  

Disadvantages:  
• Depends on move ordering  
• Still costly for large trees  

Applications:  
• Chess AI  
• Tic-Tac-Toe  
• Game engines  
• Decision-making systems  
