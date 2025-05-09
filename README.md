# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start the process.
### Step 2: Input a square matrix.
### Step 3: Compute the eigenvalues by solving the characteristic equation |A - λI| = 0.
### Step 4: For each eigenvalue, find the corresponding eigenvector using (A - λI)v = 0.
### Step 5: Display the eigenvalues and eigenvectors, then end the process.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: BOYALAKUNTLA KHAJA RASOOL
#RegisterNumber: 212224230040

import numpy as np
a = np.array([[4,2],[2,4]])
eig_value,eig_vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_value,eig_vector))
```
## Output:
![image](https://github.com/user-attachments/assets/eefab708-354d-4888-bcf7-23bbab6a6580)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
