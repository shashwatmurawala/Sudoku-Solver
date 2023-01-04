# Sudoku-Solver
Prerequisites:
Python 3.x (I used 3.9.x)
OpenCV - 4.4.0
Numpy - 1.19.3
Tensorflow - 2.5.0
Imutils - 0.5.4

For this program, I built a sudoku solver program using OpenCV. The 
program detects a sudoku board from an image and then gives an image 
the board solved. 

The program first detects a sudoku board in an image then extracts only
the board. Then it detects each of the given numbers in the board and solves
it. After the board is solved it puts the solved numbers into the original 
at the same position where the board was empty. The operations were built using
OpenCV python and Deep learning OCR detection.
