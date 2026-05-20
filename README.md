# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
import numpy as np
from scipy.linalg import lu,lu_factor,lu_piv
Get input from the user as eval(input())
Use lu_factor and lu_solve to find LU decomposition
print L,U
print x

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: G.DHARNISH
RegisterNumber: 212225040069

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: G.DHARNISH
RegisterNumber: 212225040069
'''Program to solve a matrix using LU decomposition.
Developed by: G.DHARNISH
RegisterNumber: 212225040069
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(A)
x=lu_solve((l,p),b)
print(x)

*/
```

## Output:
![lu decomposition]()****

<img width="1183" height="884" alt="image" src="https://github.com/user-attachments/assets/35abba39-3df3-4e34-a24d-12e4dd27b44b" />
<img width="982" height="786" alt="image" src="https://github.com/user-attachments/assets/e26c4ffa-09c7-4024-adf5-216f02b09629" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

