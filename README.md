# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2. From scipy package import lu().
3. Get input from user and pass it as an array.
4. Get P, L, U matrix using lu()


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: rohit g
RegisterNumber:212222240083
# To print L and U amtrix
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: rohit g
RegisterNumber:212222240083
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=eval(input()) #np.array(eval(input()))
b=eval(input())
lu,piv=lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![lu decomposition]()
![image](https://github.com/rohitgunasekaran/LU-Decomposition/assets/119404546/4e819b40-51b3-41f5-8bf2-e12e1841e55a)
![image](https://github.com/rohitgunasekaran/LU-Decomposition/assets/119404546/9b9a975e-6bf2-413a-8438-a1844ee43cf1)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

