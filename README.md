# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Harini sree N
#RegisterNumber:212225230093
import os
os.environ['OPENBLAS_NUM_THREADS']='1'
import numpy as np
n=np.array([[3,2,5],[1,1,2],[3,3,6]])

result=np.linalg.matrix_rank(n)
print(result)

```
## Output:

<img width="1375" height="827" alt="image" src="https://github.com/user-attachments/assets/48b111ea-d353-482e-8327-c9da1ff1b0d4" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

