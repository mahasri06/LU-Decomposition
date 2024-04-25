# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Mahasri P
RegisterNumber: 212223100029
*/

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
Developed by: Mahasri P
RegisterNumber: 212223100029
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv= lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
(i) To find the L and U matrix
![image](https://github.com/mahasri06/LU-Decomposition/assets/139841897/425e0478-5ffe-47ca-ba4c-390e527b2595)

(ii) To find the LU Decomposition of a matrix
![Screenshot 2024-04-25 031909](https://github.com/mahasri06/LU-Decomposition/assets/139841897/e2453831-3e71-4537-ade0-b30ebcc265e1)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

