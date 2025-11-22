# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
##Step 1: Import the numpy module to use the built-in functions for calculation

##Step 2: Prepare the lists from each linear equations and assign in np.array() 

##Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

##Step 4: End the program
 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: S.Ranjani
RegisterNumber: 25017557
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:S.Ranjani 
RegisterNumber: 25017557
'''
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu,pivot = lu_factor(a)
x = lu_solve((lu,pivot),b)
print(x)
```

## Output:
<img width="1257" height="518" alt="Screenshot 2025-11-22 175612" src="https://github.com/user-attachments/assets/7e61b87a-3484-45cc-89f6-9dc35709d78f" />
<img width="1255" height="313" alt="Screenshot 2025-11-22 175548" src="https://github.com/user-attachments/assets/863b12ed-1d4d-4af8-b8da-22b77ec351de" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

