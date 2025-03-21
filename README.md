# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. print result


## Program:
(i) To find the L and U matrix
```
Program to find the L and U maimport numpy as py
from scipy.linalg import lu
A=py.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)trix.
Developed by: ABDULRAWOOF
RegisterNumber: 212224230003

```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by:ABDULRAWOOF 
RegisterNumber: 212224230003
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
*/
```

## Output:

![Screenshot 2025-03-21 142503](https://github.com/user-attachments/assets/0a9f3ad9-8e80-4ae0-b33a-43995de1f83e)

![Screenshot 2025-03-21 142439](https://github.com/user-attachments/assets/f876eec0-374d-4549-97d8-ae5f53269111)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

