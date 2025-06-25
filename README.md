# Sudoku Solver

A command-line Sudoku solver implemented in Python using the backtracking algorithm. This program takes a partially filled 9x9 Sudoku grid as input (with zeros representing empty cells) and fills it in to produce a valid completed solution.

## Features

* Interactive user input for puzzle entry (row by row)
* Uses backtracking and recursion to solve puzzles efficiently
* Prints both the original and solved Sudoku grids in an easy-to-read format
* Handles invalid inputs gracefully and prompts the user to retry

## How to Run

1. Clone or download this repository.
2. Run the script using Python 3:

```bash
python sudoku_solver.py
```

3. Enter the Sudoku puzzle when prompted:

   * Input each row with 9 numbers separated by spaces.
   * Use 0 for empty cells.
4. View the solved Sudoku printed in the console.

## Example Input

```
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
```

## Future Improvements

* Add a graphical user interface (GUI) using Tkinter for easier puzzle input
* Implement puzzle validation before solving
* Support puzzles of different sizes (e.g., 4x4, 16x16)
* Include a puzzle generator for new Sudoku challenges



