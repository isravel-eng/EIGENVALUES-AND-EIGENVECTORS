# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy library.
### Step 2: Define the matrix A using np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the eigenvalues and eigen vectors of matrix

## Program:
---
### _Developed by: ISRAVEL Y_
### _RegisterNumber: 25018187_
---
```py
import numpy as np
matrix=np.array([[2,-3,0]
                ,[2,-5,0]   
                ,[0,0,3]])
eig_values,eig_vectors=np.linalg.eig(matrix)
print(f"Eigen values are {eig_values} and Eigen Vectors are {eig_vectors}")
```
## Output:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6016de90-6867-4019-97d5-fa3495e1667b" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
