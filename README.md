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
<img width="750" height="378" alt="{AA84B86A-0756-4EEF-91EA-8311C900A45A}" src="https://github.com/user-attachments/assets/8c7ef9cd-bd46-4e05-91ed-ed36d2daa8af" />
<img width="565" height="184" alt="{BCE8A93A-3904-42F4-8117-85CFDEE6F608}" src="https://github.com/user-attachments/assets/e0df656c-c639-4801-8396-106b40be60d1" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

