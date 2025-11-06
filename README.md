# Sudoku

## Problem 
Given a partially filled 9×9 Sudoku board, fill in the remaining cells so that:
• Each row contains digits 1-9 (no repeats)
• Each column contains digits 1-9 (no repeats)
• Each 3×3 box contains digits 1-9 (no repeats)


## Approach 
1) Find the next empty cell
2) Try numbers 1-9
3) Check constraints, basically check if the number does not break the rules of sudoku at that spot.
4) If it is valid, place it there and proceed and if it hits a deadend then we backtrack.

## Complexity 
- is_valid function is O(1) per check

## How to run, in Google Colab 
-Open 'Sudoku,ipynb' and run all cells, change the boards to try other puzzles. 
