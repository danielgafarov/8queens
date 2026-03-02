# The 8 Queens Problem
[![de](https://img.shields.io/badge/lang-de-blue.svg)](README.de.md)

The goal of the **8 Queens Problem** is to place eight queens on an 8x8 chessboard such that no two queens threaten each other. This means no two queens may share the same row, column, or diagonal. There are a total of **92 distinct solutions** to this problem.



---

### Algorithm One: Genetic Algorithm
This approach mimics the principles of natural evolution, where organisms pass their genetic information to their offspring.

* **Purpose:** This algorithm is primarily used for academic and demonstration purposes. Due to its stochastic nature, it is often less efficient for solving deterministic problems in practical applications.
* **Outcome:** It typically yields only a single solution and, in the worst-case scenario, does not guarantee finding a solution at all.
* **Performance:** Because random processes (mutation and recombination) play a central role, execution times can vary significantly between runs.

### Algorithm Two: Backtracking Search
A backtracking algorithm systematically explores potential solutions using a tree-like structure.



* **Functionality:** As soon as the algorithm determines that a specific branch cannot lead to a valid solution (because all paths within that branch share the same conflict), it discards that branch (**"pruning"**) and backtracks to the last decision point.
* **Advantages:** This algorithm is guaranteed to find **all** 92 solutions and offers a consistent, predictable execution time.
