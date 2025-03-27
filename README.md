# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SANTHOSH S
#RegisterNumber: 212224100052
import numpy as np

matrix = np.array([[2, 2], 
                   [1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(matrix)

print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```

## Output:
![Screenshot (125)](https://github.com/user-attachments/assets/8590d7b6-b16a-403b-9f77-2d68c1b645c4)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
