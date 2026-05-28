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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[3,2,5],[1,1,2],[3,3,6]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
<img width="1048" height="566" alt="{C1AC13AE-1BE4-4E5A-876F-41BA972B01C5}" src="https://github.com/user-attachments/assets/60f55d25-1a1d-4dbf-9191-020f1c94e674" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

