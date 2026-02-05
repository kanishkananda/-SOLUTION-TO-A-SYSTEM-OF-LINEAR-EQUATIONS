# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
#Program to find the solution for the given linear equations.
#Developed by: N.Kanishka
#RegisterNumber:212225230127
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
x=np.linalg.solve(A,B)
print(x)

## Output:
<img width="1879" height="959" alt="Maths Exp-1" src="https://github.com/user-attachments/assets/51086bed-2ac3-47de-b35f-ea710e241513" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

