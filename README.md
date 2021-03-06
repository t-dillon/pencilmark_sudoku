## Pencilmark Sudoku Datasets

This project contains datasets of interesting Pencilmark Sudoku puzzles.

Pencilmark Sudoku obey the same rules as standard Sudoku except clues are given
as candidate eliminations instead of filled-in cells (i.e., as negative literals
instead of positive ones).

For standard Sudoku it has been shown ([McGuire et al.](https://arxiv.org/abs/1201.0749))
that at least 17 clues are required to constrain a puzzle to a unique solution.
For pencilmark Sudoku the corresponding bound has not been proven, but it must be <= 86
since since we have 86 clue puzzles included here.

For tools for manipulating Pencilmark Sudoku see:<br>
https://github.com/dobrichev/PencilmarkSudoku/releases

For solving benchmarks and Pencilmark Sudoku puzzle generation tools see:<br>
https://github.com/t-dillon/tdoku
