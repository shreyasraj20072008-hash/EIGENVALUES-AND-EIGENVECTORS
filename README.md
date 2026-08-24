# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: BOJA RAJA G
#RegisterNumber: 212225230036
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[4,2],[2,4]])
Eigenvalue,Eigenvector=np.linalg.eig(matrix)
print("Eigen values are",Eigenvalue,"and Eigen Vectors are",Eigenvector)
~~~

## Output:
<img width="1425" height="891" alt="Screenshot 2026-08-24 181226" src="https://github.com/user-attachments/assets/9ed4226d-5dba-48cf-92f6-1fa32ea6e0f3" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
