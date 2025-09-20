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
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
b=np.array([4,5,7])

c= lu_factor(a)
x=lu_solve(c,b)
print(x)

```

## Output:
<img width="1183" height="444" alt="Screenshot 2025-09-20 082351" src="https://github.com/user-attachments/assets/6bb25a3d-f2c8-45df-82ef-f69943d6924a" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
