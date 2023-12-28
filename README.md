# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np
2. From Scipy package import lu
3. Get input from the user
4. Print result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Divya R V 
RegisterNumber: 212223100005
*/
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Divya R V
RegisterNumber: 212223100005
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),b)
print (x)

```

## Output:
Developed by: Divya R V , 
Register Number : 212223100005

![Alt text](<Screenshot 2023-12-28 201221.png>)

![Alt text](<Screenshot 2023-12-28 201309.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

