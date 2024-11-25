This project is a graphical application for solving the 8 Puzzle problem using different search algorithms. It provides a user-friendly interface built with Tkinter to visualize and interact with the puzzle, along with the implementation of algorithms like BFS, DFS, and A* (using Manhattan and Euclidean heuristics).

Table of Contents
Features
Algorithms
Installation
How to Use
File Structure
Contributing
License


Features

Interactive Puzzle Board: Visualize the puzzle state and interact with it.
Random State Generator: Generate random, solvable initial states.
User Input State: Set your own initial state manually through the UI.
Multiple Algorithms:
Breadth-First Search (BFS)
Depth-First Search (DFS)
A* Search with Manhattan and Euclidean heuristics
Runtime Statistics:
Nodes searched
Execution time
Solution cost (number of steps)
Step-by-Step Animation: Watch the puzzle get solved step-by-step.
Algorithms
Breadth-First Search (BFS): Explores all possibilities level-by-level and guarantees the shortest solution.
Depth-First Search (DFS): Explores deeper paths first, but may not guarantee the shortest solution.
A*:
Manhattan Distance Heuristic: Calculates the total Manhattan distance of tiles from their goal positions.
Euclidean Distance Heuristic: Uses the Euclidean distance for better accuracy in estimating costs.