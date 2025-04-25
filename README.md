# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy library to access linear algebra tools.
### Step 2: Create the 2×2 matrix you want to analyze.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Pragatheeshraaj D
#RegisterNumber: 212224230199
import numpy as np
a = np.array([[4, 2], [2, 4]])
values, vectors = np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values, vectors))
```
## Output:
![Screenshot 2025-04-24 185216](https://github.com/user-attachments/assets/4f7ab474-8653-4a34-91b7-940d7ed584fb)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
