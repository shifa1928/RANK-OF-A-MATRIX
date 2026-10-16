# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation


### Step 2: Prepare the lists from each linear equations and assign in np.array()

### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
#Program to find the rank of a matrix.
#Developed by: M SHIFA
#RegisterNumber:26003336
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[3,2,5],[1,1,2],[3,3,6]])
r=np.linalg.matrix_rank(A)
print(r)
## Output:
<img width="1007" height="563" alt="{AF1C9BDF-9159-4FA5-A102-CFAB33F5419E}" src="https://github.com/user-attachments/assets/8f29e140-8a60-4e1d-b92a-c2f37c9efbcf" />
<img width="775" height="195" alt="{AFF62729-9BD8-4850-8EEE-5D3395630B04}" src="https://github.com/user-attachments/assets/c996f09d-3cee-4273-aec6-18005b5a03ff" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

