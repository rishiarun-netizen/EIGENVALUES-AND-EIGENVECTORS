# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: Rishi Arun.S

#RegisterNumber: 26013829

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix = np.array([[2, -3, 0], [2, -5, 0], [0, 0, 3]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)


<img width="1478" height="593" alt="Exp-04 - Record Eigen Values and Eigen Vectors" src="https://github.com/user-attachments/assets/dec5e61d-551d-469d-b2c1-3c5eb9c48ac5" />



## Output:<img width="1332" height="175" alt="image" src="https://github.com/user-attachments/assets/c6a4fc10-69b2-4e25-877d-824130fc512d" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
