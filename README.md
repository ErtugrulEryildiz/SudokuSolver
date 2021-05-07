# Sudoku Solver

SudokuSolver is a sudoku puzzle solver that utilizes three different algorithm, namely Backtracking, Rule Based, and Boltzmann Machine.

## Run

```bash
python3 main.py <<Algorithm Type>>
```
Algorithm type must be in between 1 and 3, representing the algorithm to be used. 1-> Backtracking, 2-> Rule Based, 3-> Boltzmann Machine

## Input
Program reads the first puzzle that is provided in the generatedSudokus test file. If user wants to test their own puzzles, they should follow the same convention and place their puzzle in this file.

## Puzzle Convention
All the numbers represents the cell values in the puzzle except 0, which represents empty tiles.

[

[0, 1, 2, 3, 4, 5, 6, 7, 8], 

[0, 1, 2, 3, 4, 5, 6, 7, 8], 

[0, 1, 2, 3, 4, 5, 6, 7, 8], 

[0, 1, 2, 3, 4, 5, 6, 7, 8], 

[0, 1, 2, 3, 4, 5, 6, 7, 8], 

[0, 1, 2, 3, 4, 5, 6, 7, 8], 

[0, 1, 2, 3, 4, 5, 6, 7, 8], 

[0, 1, 2, 3, 4, 5, 6, 7, 8], 

[0, 1, 2, 3, 4, 5, 6, 7, 8], 

[0, 1, 2, 3, 4, 5, 6, 7, 8] ]
