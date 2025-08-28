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
#Developed by: BALA SARAVANAN K
#RegisterNumber: 212224230031

import numpy as np

A = np.array([[1,-3] , [3,1]])
B = np.array([0,10])

C = np.linalg.solve(A,B)

print(C)
```

## Output:
<img width="2543" height="1344" alt="Screenshot 2025-08-28 024559" src="https://github.com/user-attachments/assets/eb144e41-f4ed-4bcd-bc72-081051ce3062" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

