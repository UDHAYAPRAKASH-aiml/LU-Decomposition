# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm for L and U Matrix
```
1.import the numpy module to use the built-in-functions for calculation 
2.from scipy.linalg import lu 
3.enter the lists from each linear equation and assign in np.array()
4.print L and U Matrix
5.end the program
``````
``````
## Algorithm for LU decomposition:
1.import the numpy module to use the built-in-functions for calculation 
2.from scipy.linalg import lu 
3.enter the lists from each linear equation and assign in np.array
4.using lu_solve(), we can find L and U matrix
```
``````

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:UDHAYA PRAKASH V
RegisterNumber:24901131
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: UDHAYA PRAKSH V
RegisterNumber:24901131
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu, piv=lu_factor(A)
x = lu_solve((lu, piv), b)
print(x)
```
## Output::

(i) To find the L and U matrix:
![Screenshot (54)](https://github.com/user-attachments/assets/803feedb-0a11-45f4-87e8-9b18388235bd)
(ii) To find the LU Decomposition of a matrix
![Screenshot (53)](https://github.com/user-attachments/assets/cd42b2d2-99be-4999-9f56-e60bcb744af1)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

