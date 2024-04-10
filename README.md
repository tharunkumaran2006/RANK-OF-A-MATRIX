# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
End the program. 
## Program:
```
#Program to find the rank of a matrix.
import numpy as np
matrix = np.array([[5, -3, -10],[2, 2, -3],[-3, -1, 5]])
rank = np.linalg.matrix_rank(matrix)
print(rank)
#Developed by: Tharun V K
#RegisterNumber:212223230231
```
## Output:
![alt text](<Screenshot 2024-04-10 183408.png>)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

