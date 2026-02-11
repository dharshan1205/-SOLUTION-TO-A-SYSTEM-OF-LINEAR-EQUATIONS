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
```
#Program to find the solution for the given linear equations.
#Developed by: Dharshan R
#RegisterNumber: 212224230060
import numpy as np

A = np.array([
    [5, -3, -10],
    [2,  2, -3],
    [-3, -1, 5]
])
B = np.array([-9, 4, -1])
solution = np.linalg.solve(A, B)
solution = np.round(solution)
print(solution)

```
<img width="1289" height="714" alt="image" src="https://github.com/user-attachments/assets/c166ef30-b510-4e7b-9ef2-2c7c5bef683b" />

## Output:
<img width="1284" height="293" alt="image" src="https://github.com/user-attachments/assets/80cf1968-83e7-4eb7-b91a-f45a391e4068" />

## Result: 

Thus the solutions for the linear equations are successfully solved using python program

