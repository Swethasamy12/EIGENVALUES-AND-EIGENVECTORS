# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.

### Step 2: Prepare the lists from each equations and assign in np.array().

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:swetha.C 
#RegisterNumber:24901183
import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
e_values,e_vectors=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(e_values,e_vectors))
```
## Output:

![Screenshot 2024-12-26 045753](https://github.com/user-attachments/assets/20daa63e-02f3-446b-90f1-7ad167bdee47)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
