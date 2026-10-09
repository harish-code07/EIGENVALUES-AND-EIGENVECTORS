# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Importing os and numpy module packages.
### Step 2: Creating the given matrices in code.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the result.

## Program:
####Program to find the eigen values and eigen vectors.
#Developed by:Harish Bakavadh J
#RegisterNumber:26007865
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

## Output:<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5c7dfb87-31ca-46f2-ad5c-f0b95f1e7532" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
