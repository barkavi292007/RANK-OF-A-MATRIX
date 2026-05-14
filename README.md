# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Algorithm:

### Step 1:

Import the numpy module.

### Step 2:

Create the matrix using `np.array()`.

### Step 3:

Use `np.linalg.matrix_rank()` to find the rank of the matrix.

### Step 4:

Print the rank of the matrix.
 
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(A)
print(rank
```
## Output:
<img width="1237" height="804" alt="Screenshot 2026-05-14 105200" src="https://github.com/user-attachments/assets/2e390188-54f3-4438-ad39-0d11a65f0c07" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

