# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import the numpy module to use the built-in functions for calculation
### Step 2: 
prepare the lists from each inverse of matrix and assign in np.array()
### Step 3: 
using the np.linalg.solve().we can find the solution
### Step 4: 
End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: kishore
#RegisterNumber:21500479
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
s=np.linalg.inv(A)
print(s)
```
## Output:
![output](./pg1.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

