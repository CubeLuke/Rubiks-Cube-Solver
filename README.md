# Rubiks-Cube-Solver
Rubik's Cube Solver coded in Python.  
Solver Coded by Lucas Liberacki and Tom Brannan  

To run the Solver, run the cube.py file. The GUI will automatically start up. If you get errors, there is a chance that you do not have tkinter installed. That is necessary to have in order to run the GUI.

###Features
Just read the instructions to see some of the features that are included in the Solver.
Various features included are:  
*User or program generated scrambles  
*The ability to make custom moves  
*The ability to hit either the solve button, or each step of the solve to see it solve step-by-step  
*The ability to run simulations with a user defined amount of solves (be careful, too many could make the program freeze)  
*Ability to copy scrambles or solutions to the clipboard, as well as view externally.  
*Clicking on the 2D cube will allow you to see the other bottom tiles that are not normally visible  

<p align="center">
	<img src="https://cloud.githubusercontent.com/assets/10378593/5694175/4f15d546-9914-11e4-83ea-e85d91236071.png" alt ="Solver Screenshot"/>
</p>


###Various Commands
If you don't want to use the GUI, you can also just type function commands in the interpreter. Here are some of the useful ones:  
*print_cube()   Prints the cube in text format  
*scramble()     You can either provide a number, a scramble in string format, or nothing for a 25 move default scramble  
get_scramble()  Prints the previous scramble  
solve()         Will solve the cube  
get_moves()     Prints out the Solution that was generated upon using solve()  
simulation(num) The number provided is the amount of solves you want to simulate. Will return you the best solve with it's scramble, as well as the worst solve and it's scramble.  


The Solver itself is based upon a CFOP (Fridrich) method of solving. It solves the Cross, does the F2L step, does a 2-look OLL, and a 2-look PLL.  As for notation, basic notation used in the cubing world is used, however, a counterclockwise move can be denoted with either an apostrophe (standard way), or using the letter i (denoting i for inverse).
