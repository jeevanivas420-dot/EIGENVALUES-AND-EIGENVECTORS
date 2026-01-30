# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program and import the NumPy library.
### Step 2: Read the square matrix elements and store them in a NumPy array.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors and stop the program.

## Program:
```python
import numpy as np

A = np.array([[2, -3, 0],
              [2, -5, 0],
              [0,  0, 3]])

eigen_values, eigen_vectors = np.linalg.eig(A)

print(f"Eigen values are {eigen_values} and Eigen Vectors are {eigen_vectors}")
```

## Output:
<img width="1238" height="822" alt="image" src="https://github.com/user-attachments/assets/207359ef-2758-4c68-babf-79f88772fee0" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
