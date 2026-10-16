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
<img width="782" height="406" alt="{1ABF06FB-EE82-4524-9E40-E4051982D45F}" src="https://github.com/user-attachments/assets/3ddded2a-6da9-4524-961e-419098c4334c" />
<img width="308" height="220" alt="{E35788E9-1537-40E0-8AE6-1B4277FA714B}" src="https://github.com/user-attachments/assets/4dde349d-9751-4704-8641-94b61fa86912" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

