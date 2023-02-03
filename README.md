# Sudoku-solver

Built with Python, using the backtracking algorithm

## **How it works**

Starting with an incomplete board:

* Find the first empty space on the board (if there's one)
* Try to place the digits 1 through 9 in that space
* Check if that digit is valid in the current spot based on the current board
* Attempt the board with backtrack
  + If the digit is valid, recursively attempt to fill the board using steps 1-3.
  + If it is invalid, reset the square that was just filled and go back to the previous step.
* Sudoku is solved when the board is full

## Installation and use

> pip install -r requirements.txt
> python3 sudoku-solver.py

