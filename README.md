# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module and scipy.linalg module to use the built-in functions for calculation.
2. Prepare the lists from each linear equations and assign in np.array()
3. Perform scipy.linalg.lu() to find the pivot table, lower traingle and upper triangle matrix.
4. End the Program

## Program:
'''Program to find L and U matrix using LU decomposition.
Developed by: Aaron Rajesh R
RegisterNumber: 23008897
''' 

import numpy as np 
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
'''Program to solve a matrix using LU decomposition.
Developed by: Aaron Rajesh R
RegisterNumber: 23008897
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor ,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

## Output:
![Screenshot 2023-12-31 202848](https://github.com/Aaron-0111/LU-Decomposition/assets/149347631/f687117d-774e-4126-a58b-958ddfbd1fa1)

![Screenshot 2023-12-31 202417](https://github.com/Aaron-0111/LU-Decomposition/assets/149347631/2c222939-c65f-4c5f-a78c-e9abfdace356)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

