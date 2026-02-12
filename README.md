# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Monisha D 
RegisterNumber: 212225240090
*/

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Monisha D 
RegisterNumber: 212225240090
*/

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu, piv),B)
print(X)
```

## Output:
![lu decomposition]()
(i) To find the L and U matrix:

<img width="1242" height="578" alt="Screenshot 2026-02-12 201911" src="https://github.com/user-attachments/assets/cfac075b-a935-4741-9ced-1785b4225912" />

(ii) To find the LU Decomposition of a matrix:

<img width="1238" height="326" alt="Screenshot 2026-02-12 201930" src="https://github.com/user-attachments/assets/8f3a4d4b-a323-4721-873b-75a91ddbf960" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

