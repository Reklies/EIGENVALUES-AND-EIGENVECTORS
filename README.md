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
```
#Program to find the eigen values and eigen vectors.
#Developed by: Reklies J
#RegisterNumber:23000590
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot 2023-12-19 154637](https://github.com/Reklies/EIGENVALUES-AND-EIGENVECTORS/assets/147139232/5b13ddb7-ded6-42a9-a7a0-d63fb16c92cf)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
