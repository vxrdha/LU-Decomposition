# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.  Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
4. End the program

## Program:
(i) To find the L and U matrix
```
Input
[[3, 2, 7], [2, 3, 1], [3, 4, 1]]


Program to find the L and U matrix.

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

Developed by: AMSAVARADHAN M

RegisterNumber: 25011322

(ii) To find the LU Decomposition of a matrix
```
Input
[[3, 2, 7], [2, 3, 1], [3, 4, 1]]
[4, 5, 7]

Program to find the LU Decomposition of a matrix.
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```
Developed by: AMSAVARADHAN M

RegisterNumber: 25011322

## Output:

<img width="1920" height="1020" alt="Screenshot 2025-12-17 095432" src="https://github.com/user-attachments/assets/f7260202-5859-4171-b77d-5554f8b0deb4" />
<img width="1920" height="1020" alt="Screenshot 2025-12-17 095453" src="https://github.com/user-attachments/assets/2cf28c71-32e5-480e-b7ee-d3dc0de9697f" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

