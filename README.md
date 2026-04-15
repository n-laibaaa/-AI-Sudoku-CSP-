🧩 Sudoku Solver using CSP

This project implements a Sudoku Solver using Constraint Satisfaction Problem (CSP) techniques. It solves Sudoku boards of varying difficulty using:

Backtracking Search
Forward Checking
Arc Consistency (AC-3)
🚀 Features
Solves Easy, Medium, Hard, and Very Hard Sudoku boards
Uses MRV (Minimum Remaining Values) heuristic
Applies AC-3 for domain reduction
Implements Forward Checking for constraint propagation
Tracks:
Number of Backtracking Calls
Number of Backtracking Failures
📂 Project Structure

├── sudoku_csp.py

├── easy.txt

├── medium.txt

├── hard.txt

├── veryhard.txt

🧠 Approach

The Sudoku problem is modeled as a CSP:

Variables: Each cell in the 9×9 grid

Domain: Values from 1 to 9

Constraints:

No repeated values in any row

No repeated values in any column

No repeated values in any 3×3 subgrid

Techniques Used

AC-3 Algorithm: Reduces domains before search

Backtracking: Searches for valid assignments

Forward Checking: Eliminates invalid values early

MRV Heuristic: Chooses the most constrained variable first

▶️ How to Run

Make sure Python is installed

Place all .txt boards in the same directory

Update file paths in code (if needed)

Run the program:

python sudoku_csp.py
