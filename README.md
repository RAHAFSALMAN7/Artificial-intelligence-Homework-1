# Artificial-intelligence-Homework-1
This assignment focuses on implementing and analyzing search algorithms to solve a grid-based pathfinding problem and a sorting problem formulated as a search problem. The assignment includes various exercises that require the application of A* algorithm, evaluation of heuristics, and analysis of state spaces in different formulations.
Details
Grid-Based Pathfinding Problem (A Algorithm)*

Objective: Implement the A* search algorithm to find the optimal path from a start position to a goal position in a grid with obstacles.
Heuristic: Manhattan distance.
Details:
The grid is defined with some cells blocked.
The agent can move up, down, left, or right.
Implement the A* algorithm to find the shortest path and explain why A* is optimal for this problem.
Coloring a 9x9 Grid

Objective: Formulate the problem of coloring a 9x9 grid, ensuring each 3x3 sub-square is uniformly colored and neighboring sub-squares are different colors.
Exercises:
Compute the size of the state space for the straightforward formulation.
Reformulate by considering only unique colorings, and evaluate the performance of breadth-first graph search and iterative deepening tree search.
Abstract further to consider only uniform sub-square colorings and compute the state space.
Calculate the number of valid solutions.
Provide a translation from abstracted solutions to the original problem solutions.
Sorting as a Search Problem

Objective: Analyze the sorting of a list of integers using search algorithms.
Initial State: 2,6,1,5
Goal State: 1,2,5,6
Operator: Exchange two consecutive integers.
Heuristic: Number of integers in the wrong location.
Exercises:
Determine if the heuristic is admissible.
Calculate the branching factor.
Apply hill climbing to solve the problem.
Code Implementation and Instructions
Language: Python
Instructions:
Ensure Python is installed on your system.
Use Visual Studio Code with the Python extension for development.
Create a new Python file and paste the provided code for the A* algorithm.
Run the script in the terminal within VS Code to see the results.
Conclusion
This assignment aims to deepen the understanding of search algorithms and their applications in problem-solving. By working through these exercises, students will gain practical experience in implementing algorithms, evaluating heuristics, and formulating problems in computational terms. The hands-on approach reinforces theoretical concepts and enhances problem-solving skills in artificial intelligence.

