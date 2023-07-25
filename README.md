# RANK-OF-A-MATRIX
## AIM:
To write a python program to find the rank of a matrix
## EQUIPMENTS REQUIRED:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## PROGRAM:
```
#Program to find the rank of a matrix.
#Developed by: Daksha Subbaian 
#RegisterNumber: 23003584
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
result=np.linalg.matrix_rank(A)
print(result)
```
## OUTPUT:
![output](/output02.png)

## RESULT:
Thus the rank for the given matrix is successfully solved by  using a python program.

