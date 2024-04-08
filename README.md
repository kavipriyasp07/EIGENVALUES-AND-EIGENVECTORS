# EIGENVALUES-AND-EIGENVECTORS
# Date:06/04/2024
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : importing the NumPy library
### Step 2: Define the given matrix A.
### Step 3:  Use np.linalg.eig(A) to find the eigenvalues and eigenvectors.
### Step 4: print and end the program.
# Question:
write a program to find the eigenvalues and associated eigenvectors for the matrix 
[2,2],[1,3]

## Program:
```
Developed by:kavi priya s.p
RegisterNumber:2305002011 
```
```python
import numpy as np
a=np.array([[2,2],[1,-3]])
value,vector=np.linalg.eig(a)
print("Eigenvalues are {} and Eigenvectors are {}".format(value,vector))
```
## Output:
![Screenshot 2024-04-08 161239](https://github.com/kavipriyasp07/EIGENVALUES-AND-EIGENVECTORS/assets/155508590/85e2d8ac-1abd-4fc6-a4d5-f8855363b3d9)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
