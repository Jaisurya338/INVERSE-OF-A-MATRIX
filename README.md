# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
##Step 1:
Import the numpy module to use the built-in functions for calculation

###Step 2:
Prepare the lists from each linear equations and assign in np.array()

###Step 3:
Using the np.linalg.inv(matrix), we can find the inverse of the given matrix

###Step 4:
End the program

## Program:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

# Define the matrix
matrix = np.array([[2, 1, 1],
                   [1, 1, 1],
                   [1, -1, 2]])

inverse_matrix = np.linalg.inv(matrix)

print(inverse_matrix)
## Output:
<img width="787" height="862" alt="image" src="https://github.com/user-attachments/assets/8cf78d87-1f98-4611-96db-d31ebbce5ea4" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

