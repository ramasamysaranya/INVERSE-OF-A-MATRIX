# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the os and numpy libraries. 
### Step 2: Define the matrix using np.array() and store it in the variable matrix.
### Step 3: Use the np.linalg.inv() function to calculate the inverse of the given matrix and store the result in the variable result.
### Step 4: Display the inverse matrix using the print() function.

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[2, 1, 1],[1, 1, 1],[1, -1, 2]])
result=np.linalg.inv(matrix)
print(result)
```
## Output:
<img width="965" height="350" alt="image" src="https://github.com/user-attachments/assets/b9f6e343-d5fd-42ed-b11c-6d68b66e9219" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

