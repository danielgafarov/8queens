# Eight Queens Problem
[![de](https://img.shields.io/badge/lang-de-red.svg)](https://github.com/danielgafarov/8queens/blob/main/README-de.md)

The goal of the Eight Queens Problem is to place eight queens on an 8x8 chessboard so that no two queens attack each other. This means no two queens can share the same row, column or diagonal. There are a total of 92 solutions to this problem.
### Algorithm One: Genetic Algorithm
This approach mimics nature and how organisms inherit their genes to their offspring. This algroithm has more of an educational purpose since it only yields one solution and in the worst case it doesn't find any solution at all. Because genetics involve a lot of randomness the run time for this algorithm fluctuates heavily.
### Algorithm Two: Backtracking Search
A Backtracking Algorithm builds possible solutions using a tree-like system. Once it recognizes that a branch of this tree cannot create any solutions because all of them share the same flaws it dismisses this branch and starts looking into another branch of possible solutions. This algorithm finds all solutions and always takes the same amount of time.

