AI Assignment 4
UTA ID: 1001666614
NET ID: sxr6615

Language Used: Python 2.4

Code Structure:

Program has been constructed using 3 files namely maxconnect4.py, MaxConnect4Game.py and scorecalc.py
maxconnect4.py consists of the main game mode functions that will be called as well as the main function.
MaxConnect4Game.py has the function for minimax with alpha-beta as well as the evaluation function.
scorecalc.py consists the similar code as the count_score function in MaxConnect4Game.py but with an additional state argument which is used in the alpha-beta function.

How to run the code:
The code can be compiled and executed as follows:

$python maxconnect4.py interactive inputfile.txt computer-next/human-next depth_level for Interactive Mode and
$python maxconnect4.py one-move inputfile.txt outputfile.txt depth_level for One-Move Mode

Reference:

http://aima.cs.berkeley.edu/python/games.html
https://inventwithpython.com/chapter10.html
https://github.com/Cledersonbc/tic-tac-toe-minimax
https://omega.uta.edu/~gopikrishnav/classes/common/4308_5360/slides/Game_Search.pdf
https://codereview.stackexchange.com/questions/24764/tic-tac-toe-victory-check
