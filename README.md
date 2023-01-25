# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
import the numpy module to use the build in function for calculation.
### Step 2: 
prepare the lists from each linear equation and assign in np.array().
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program.

## Program:
~~~
#Program to find the rank of a matrix.
#Developed by: panimalar.p
#RegisterNumber:22009107
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
~~~

## Output:

![Screenshot (159)](https://user-images.githubusercontent.com/121490826/214577976-500b42b9-7176-4eaa-b24b-c45197a93790.png)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

