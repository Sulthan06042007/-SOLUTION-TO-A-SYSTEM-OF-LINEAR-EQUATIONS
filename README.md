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
import numpy as np
#define the cofficients of the equationms
A = [[1,3],[2,5]]
B = [5, -3]
C = np.linalg.solve(A,B)
print(C)
```

## Output:
![image](https://github.com/Sulthan06042007/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/144980103/70c38d26-cfce-48a9-99b4-a544653f06db)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

