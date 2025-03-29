# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from the matrix and assign in np.array()

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program. 

## Program:
```
import numpy as np

# Define the matrix
A = np.array([[2,2],[1,3]])

# Compute eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(A)

# Display results
print("Eigen values are", eigenvalues,"and Eigen Vectors are",eigenvectors)
```
## Output:
![Screenshot 2025-03-29 072336](https://github.com/user-attachments/assets/3fd26ae8-25e2-43df-b397-c83bf725b2a7)

# Developed by:Blessing S 
 # RegisterNumber:212224230039



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
