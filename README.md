# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Firstly import numpy as np and import scipy linalg as lu
2. Get the input from the user 
3. Give the appropriate formula to the program
4. Print the L and U matrix 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: M.PRANATHI
RegisterNumber: 22005710
*/
import numpy as np
from scipy.linalg import lu
arr=eval(input())
a=np.array(arr)
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: M.PRANATHI 
RegisterNumber: 22005710
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=eval(input())
res=lu_factor(a)
solution=lu_solve(res,b)
print(solution)
```

## Output:
!['OUTPUT'](/landu.png)
!['OUTPUT'](/ludecomposition.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

