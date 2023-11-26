# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import Numpy as np
### Step 2: 
Define matrix A.
### Step 3: 
Calculate the inverse using np.linalg.inv(A)
### Step 4: 
Display the inverse matrix

## Program:
``````
#Program to find the inverse of a matrix.
#Developed by: abdullah.R
#RegisterNumber:23013613
import numpy as np
matrix=np.array([[1,0,3,],
                 [-1,2,-2],
                 [2,3,-1]])
inverse=np.linalg.inv(matrix)
print(inverse)
``````
## Output:
![Alt text](<Screenshot 2023-11-24 233009.png>)
## Result:
Thus the inverse of given matrix is successfully solved using python program

