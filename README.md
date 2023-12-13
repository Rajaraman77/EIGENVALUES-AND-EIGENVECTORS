# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Enter the given matrix lists and assign it to a variable.
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: RAJARAMAN V
#RegisterNumber:23014299
import numpy as np
a=[4,2],[2,4]
b,c=np.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",c)
```
## Output:
![Screenshot 2023-12-13 093654](https://github.com/Rajaraman77/EIGENVALUES-AND-EIGENVECTORS/assets/150319383/0656b5bd-c552-4c66-9e2e-1339bf67c8fc)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
