# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
    Import the numpy module to use the build-in functions for calculation
### Step 2:
    Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
    Using the np.linealg.solve(),we can find the solution
### Step 4: 
    End the program
## Program:
```Python
#Program to find the solution for the given linear equations.
#Developed by:Ayshwariya.J 
#RegisterNumber:24901138
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
res=np.linalg.solve(a,b)
print(res)
```
### Output:
![alt text](<Screenshot 2024-11-02 120815.png>)

## Result: 
Thus the solution for the linera equations are successfully solved using python program

