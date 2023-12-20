# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.matrix_rank(),we can find the solution.
### Step 4: 
End the program
## Program:
```Python
#Program to find the rank of a matrix.
#Developed by: STANLEY S
#RegisterNumber: 23014354
import numpy as np
A=np.array([[3,2,5],[1,1,2],[3,3,6]])
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![Screenshot 2023-12-20 080952](https://github.com/STANLEY-13/RANK-OF-A-MATRIX/assets/148198816/c7d93c68-36d6-410e-826e-d05ad35b4f36)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

