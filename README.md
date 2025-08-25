# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 : Import the numpy module to use the built-in functions for calculation
Step 2: Prepare the lists from the matrix and assign in np.array()
Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
Step 4: End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: HARI PRASATH P
#RegisterNumber:212224230084

import numpy as np
A=np.array([[2,2],[1,3]])
b,c=np.linalg.eig(A)
print("Eigen values are", b, "and Eigen Vectors are",c)
```

## Output:
<img width="1237" height="783" alt="Screenshot 2025-08-25 142005" src="https://github.com/user-attachments/assets/b0aefb1f-cb90-4baa-b1b7-e459a04d220e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
