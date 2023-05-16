# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step1 : 
Import numpy module as np
### Step 2: 
Write the given matrix using np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigen values and vectors

## Program:
#Program to find the eigen values and eigen vectors.

#Developed by: Dharini PV

#RegisterNumber: 212222240024

import numpy as np

a = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,vectors = np.linalg.eig(a)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
![Screenshot 2023-05-16 085541](https://github.com/DHARINIPV/EIGENVALUES-AND-EIGENVECTORS/assets/119400845/6540ce0b-bf1b-42ed-bc21-b93562eb70ac)
![Screenshot 2023-05-16 085603](https://github.com/DHARINIPV/EIGENVALUES-AND-EIGENVECTORS/assets/119400845/7ef43899-9839-45bc-ace6-47fdcce8975a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
