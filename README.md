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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
B=[-9,4,-1]
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([[-9,4,-1]])
x=np.linalg.solve(A,B)
print(x)
```

## Output:
<img width="1247" height="681" alt="image" src="https://github.com/user-attachments/assets/dda1f672-f0d9-4e23-be4d-ac27563cd929" />
<img width="1191" height="272" alt="image" src="https://github.com/user-attachments/assets/cf0e5ce3-6a81-42b7-928a-d2c248c6c500" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

