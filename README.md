# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## step1 : Start the program.

## Step 2: prepare the lists from the each inverseof a matrix and design in ip.array().

## Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

## Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Dilip sanjay
#RegisterNumber: 212223240032
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```

## Output:
![image](https://github.com/dilipsanjay/EIGENVALUES-AND-EIGENVECTORS/assets/155506948/cea28afe-3bcd-4348-82f4-d89c67a1fdd1)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
