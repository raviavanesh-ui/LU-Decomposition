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
Developed by:Avanesh.R 
RegisterNumber: 212225240018
*/

import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Avanesh.R
RegisterNumber: 212225240018
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/9d15cb48-c880-4112-815f-2def4b3d44a9" />



<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/bb01c627-3024-495b-9e3d-d647f7e93b35" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

