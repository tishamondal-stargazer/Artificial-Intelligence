# Theory – A* Search Algorithm

Search algorithms are important techniques in Artificial Intelligence used to explore possible solutions to a problem.

Search algorithms are mainly classified into two categories:

## Uninformed Search

Uninformed search algorithms do not use additional information about the goal state. They explore the search space blindly.

Example:
Breadth First Search (BFS)

## Informed Search

Informed search algorithms use heuristic information to guide the search process towards the goal state more efficiently.

Example:
A* Search Algorithm

## A* Search Algorithm

A* (A-Star) is one of the most popular search algorithms used in Artificial Intelligence for pathfinding and graph traversal.

It evaluates nodes using the following formula:

f(n) = g(n) + h(n)

Where:

* g(n) is the cost from the start node to the current node
* h(n) is the heuristic estimate from the current node to the goal
* f(n) is the total estimated cost

The algorithm selects the node with the lowest f(n) value and expands it.

## Advantages

* Finds optimal path
* Efficient compared to uninformed search
* Reduces unnecessary exploration

## Disadvantages

* Requires high memory usage
* Performance depends on heuristic function
