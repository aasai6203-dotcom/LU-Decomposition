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
Developed by: Aarthi A
RegisterNumber:212225220001

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Aarthi A
RegisterNumber: 212225220001
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

*/
```

## Output:
<img width="761" height="869" alt="Screenshot 2026-05-16 093151" src="https://github.com/user-attachments/assets/57f6807f-f565-4538-8e47-54494f6da3ed" />
<img width="604" height="652" alt="Screenshot 2026-05-16 093200" src="https://github.com/user-attachments/assets/ec19322e-1fce-440b-9510-ee6a2f4209db" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

