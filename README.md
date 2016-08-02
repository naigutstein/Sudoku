# Sudoku

This is a Sodoku solver, which inputs an incomplete Sudoku board and returns the complete solution. <br>
You can choose from using a few different heuristics to solve the board: <br>
1. Backtracking <br>
2. Forward Checking <br>
3. MRV (minimum remaining values) <br>
4. MCV (most constrained variable-degree) <br>
5. LCV (least constrained value) <br>

To run:
<p> >>> execfile("SudokuSolver.py") </p> 
<p> #choose which board from input_puzzles you wish to use (for example "input_puzzles/easy/4_4.sudoku") </p> 
<p> >>> sb = init_board("input_puzzles/easy/4_4.sudoku") </p> 
<p> #to see initial board </p> 
<p> >>> sb.print_board() </p> 
<p> #solver(board, forward_checking, MRV, MCV, LCV) </p> 
<p> #set heuristics you want to use as True and others as False. For example: FC = True and MRV = True </p>
<p> >>> fb = solve(sb, True, True, False, False) </p>
<p> >>> fb.print_board </p>
