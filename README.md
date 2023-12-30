# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include
   the package in that variable.
4. print the variable 'X'

## Program:
```python
(i) To find the L and U matrix
Program to find the L and U matrix.
Developed by: Swaminathan V
RegisterNumber: 23000747
#To print L and U matrix
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```python
Program to find the LU Decomposition of a matrix.
Developed by: Swaminathan V
RegisterNumber: 23000747
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu,piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
```

## Output:
![LU Decompositiion](https://github.com/SwaminathanV23000747/LU-Decomposition/assets/148931113/21a3527a-d4ef-4d6c-88b5-0e78703bb061)
![LU CODE 2](https://github.com/SwaminathanV23000747/LU-Decomposition/assets/148931113/61410618-b40a-45ef-8176-2818293011ef)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

