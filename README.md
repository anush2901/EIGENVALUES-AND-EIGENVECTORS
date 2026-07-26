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

#Program to find the eigen values and eigen vectors.
#Developed by: VANISHAA HARSHINI.B.R
#RegisterNumber: 212225040481
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
matrixA=np.array([[4,2],[2,4]])
eigenValue,eigenVector=np.linalg.eig(matrixA)
print("Eigen values are", eigenValue, "and Eigen Vectors are", eigenVector)

```

## Output:
![alt text](<Screenshot 2026-07-26 204501.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
