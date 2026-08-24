# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Import the required libraries and create the given matrix.

Step 2: Find the inverse of the matrix using np.linalg.inv().

Step 3: Store the inverse matrix in the variable b.

Step 4: Print the inverse of the matrix.
## Program:
#Program to find the inverse of a matrix.
#Developed by: VIJAY D
#RegisterNumber: 212225230300
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
b=np.linalg.inv(a)
print(b)
## Output:
<img width="488" height="217" alt="image" src="https://github.com/user-attachments/assets/1a499f8f-fd15-4aa4-bdf4-c5806e696793" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

