# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1:  Import the numpy module to use the built-in functions for calculation

### Step 2: Prepare the lists from each linear equations and assign in np.array()

### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4:  End the program

## Program:
```
#Program to find the rank of a matrix.
#Developed by: NITHISH S
#RegisterNumber:212224240105

import numpy as np
def find_rank(matrix):
    return np.linalg.matrix_rank(matrix)
    
matrix = [[1,2,3],[3,6,9]]
rank = find_rank(matrix)
print(rank)
```
## Output:

<img width="262" height="90" alt="image" src="https://github.com/user-attachments/assets/404123cb-7071-4c50-859f-6c208c5fe5e7" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

