# 8-Puzzle Solver using UCS and IDS
This project focuses on solving the 8-Puzzle Problem, a well-known problem in artificial intelligence and search algorithms. The problem is solved using two uninformed search algorithms:

# Uniform Cost Search (UCS)
# Iterative Deepening Search (IDS)

The goal is to rearrange tiles in a 3x3 grid to match a predefined goal state by moving a blank tile (B) in any direction (up, down, left, right).

Problem Overview
The puzzle starts with an initial configuration:

css
Copy
Edit
1 3 4
2 B 5
8 6 7
The desired goal state is:

css
Copy
Edit
1 2 3
4 5 6
7 8 B
The solution path is determined by the sequence of moves required to reach the goal state from the initial state.

# Algorithms Explained

Uniform Cost Search (UCS):
Explores nodes by expanding the least cost path first.
Guarantees an optimal solution by expanding paths in increasing order of cost.
Uses a priority queue to manage node expansions.

Iterative Deepening Search (IDS):
Combines the depth-first search (DFS) and breadth-first search (BFS) techniques.
Searches incrementally with increasing depth limits until the goal is found.
Memory-efficient but may require multiple re-expansions of nodes.
Features
# State Visualization: 
The project displays each state of the puzzle as the algorithms explore possible moves.
# Comparison of Steps: 
Reports the number of steps each algorithm took to reach the goal, enabling comparisons of performance.
# Optimality: 
Highlights which algorithms perform better for different configurations in terms of both steps and memory usage.
# Project Outcome
This project demonstrates that UCS and BFS are optimal for finding the shortest path when all edge costs are equal. DFS and IDS, though potentially faster, may not guarantee the shortest path in such scenarios.
