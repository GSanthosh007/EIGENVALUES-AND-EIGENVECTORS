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
```
#Program to find the eigen values and eigen vectors.
#Developed by: SANTHOSH G
#RegisterNumber: 212223240152
import numpy as np
A = np.array([[-2, 2, -3],
              [2, 1, -6],
              [-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(eigenvalues , eigenvectors))


```
## Output:
![Screenshot 2024-04-10 211250](https://github.com/GSanthosh007/EIGENVALUES-AND-EIGENVECTORS/assets/147527586/3535127b-1b25-40da-90da-128f4439a94f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
