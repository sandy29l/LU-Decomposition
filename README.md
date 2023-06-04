# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy library using import statement.

2.From scipy package import lu(). 

3.Get input from user and pass it as an array. 

4.Get P, L, U matrix using lu() 5.Print L and U matrix.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Santhosh.L
RegisterNumber: 212222100046
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
p,l,u=lu(arr)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: santhosh L
RegisterNumber: 212222100046
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array(eval(input()))
b=np.array(eval(input()))
lu,p=lu_factor(arr)
res=lu_solve([lu,p],b)
print(res)
```

## Output:
## (i) To find the L and U matrix
![Screenshot (8)](https://github.com/sandy29l/LU-Decomposition/assets/123359969/b3079ee4-794c-4cc3-9729-3c40c5cc625a)
## (ii) To find the LU Decomposition of a matrix
![Screenshot (9)](https://github.com/sandy29l/LU-Decomposition/assets/123359969/209890ec-d8fb-4bdb-97f2-9abdb90db6e6)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

