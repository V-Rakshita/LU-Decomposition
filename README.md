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
Developed by: V. RAKSHITA
RegisterNumber: 24900032
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: V. RAKSHITA
RegisterNumber: 24900032
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input())) 
lu, piv = lu_factor(A)
X = lu_solve((lu, piv),B)
print(X)
*/
```

## Output:
![lu decomposition]()

(i) To find the L and U matrix
![FIND L AND U MATRIX](https://github.com/user-attachments/assets/678c74bb-6227-45d2-b07d-cbda1782681f)

(ii) To find the LU Decomposition of a matrix
![LU DECOMPOSITION](https://github.com/user-attachments/assets/b742b406-d543-4850-bb41-b2bd8bef7895)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

