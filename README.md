# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy

A=numpy.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,Vectors=numpy.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:<img width="1362" height="703" alt="{CC03D431-C5C3-4CF7-B771-2A143F5FD062}" src="https://github.com/user-attachments/assets/2e00b790-0c45-467b-b239-c711d6b32943" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
