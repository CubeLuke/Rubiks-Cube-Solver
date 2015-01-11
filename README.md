# Rubiks-Cube-Solver
Rubik's Cube Solver coded in Python.
Solver Coded by Lucas Liberacki and Tom Brannan

To run the Solver, run the cube.py file. The GUI will automatically start up. If you get errors, there is a chance that you do not have tkinter installed. That is necessary to have in order to run the GUI.

Just read the instructions to see some of the features that are included in the Solver.
Various features included are:
*User or program generated scrambles  
*The ability to make custom moves  
*The ability to hit either the solve button, or each step of the solve to see it solve step-by-step  
*The ability to run simulations with a user defined amount of solves (be careful, too many could make the program freeze)  
*Ability to copy scrambles or solutions to the clipboard, as well as view externally.  
*Clicking on the 2D cube will allow you to see the other bottom tiles that are not normally visible  


If you don't want to use the GUI, you can also just type function commands in the interpreter. Here are some of the useful ones:
*print_cube()   Prints the cube in text format  
*scramble()     You can either provide a number, a scramble in string format, or nothing for a 25 move default scramble  
get_scramble()  Prints the previous scramble  
solve()         Will solve the cube  
get_moves()     Prints out the Solution that was generated upon using solve()  
simulation(num) The number provided is the amount of solves you want to simulate. Will return you the best solve with it's scramble, as well as the worst solve and it's scramble.  
