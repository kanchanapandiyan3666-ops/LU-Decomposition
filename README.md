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
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: KANCHANA P
RegisterNumber: (25018334)
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```

## Output:
<img width="1270" height="780" alt="Screenshot 2025-12-10 192922" src="https://github.com/user-attachments/assets/e4c0d0cc-2083-4156-a87e-f6458895cd0d" />
<img width="1270" height="780" alt="Screenshot 2025-12-10 192922" src="https://github.com/user-attachments/assets/9a783c02-f713-4dc4-9e0e-359699296996" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

