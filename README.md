# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the NumPy module to use its built-in mathematical functions.
### Step 2: 
Create the matrix using np.array() and store it in a variable.
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the eigenvalues and eigenvectors using the print() function.
### Step 5:
End the program.

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))


```

## Output:
<img width="1482" height="967" alt="image" src="https://github.com/user-attachments/assets/3c0fb775-246c-40fe-b670-c9135ffdc8c3" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
