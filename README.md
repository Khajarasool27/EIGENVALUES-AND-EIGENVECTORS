# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program and import the necessary NumPy library.
### Step 2: Define the square matrix for which eigenvalues and eigenvectors need to be found.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors.
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
