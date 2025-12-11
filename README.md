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

```

## Output:
<img width="1352" height="793" alt="Screenshot 2025-12-10 192904" src="https://github.com/user-attachments/assets/563a1752-f176-42cc-b2ef-2a417c7b8691" />
<img width="1270" height="780" alt="Screenshot 2025-12-10 192922" src="https://github.com/user-attachments/assets/e4c0d0cc-2083-4156-a87e-f6458895cd0d" />
<img width="1073" height="711" alt="Screenshot 2025-12-10 192949" src="https://github.com/user-attachments/assets/1b88148e-bd77-4d18-914a-2b99807e8f56" />
<img width="1342" height="629" alt="Screenshot 2025-12-10 193002" src="https://github.com/user-attachments/assets/374ba94a-2582-442a-b8ef-08dd7a914a0b" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

