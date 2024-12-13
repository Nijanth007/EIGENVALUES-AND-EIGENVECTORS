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
import numpy as np

# Define the matrix
A = np.array([[2, 2], [1, 3]])

# Calculate eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(A)

# Print the results
print("Eigen values are", eigenvalues,end=" ")
print("and Eigen Vectors are", eigenvectors)


## Output:
![image](https://github.com/user-attachments/assets/d518b849-9b80-43dd-a482-47587adf7338)
![image](https://github.com/user-attachments/assets/1a54957c-0158-45ef-88de-84b0b796ca39)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
