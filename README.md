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
```'''Program to find L and U matrix using LU decomposition.
Developed by:tom francies xaviour l 
RegisterNumber: 212223110060
'''
import numpy as np
from scipy.linalg import lu
A =np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: tom francies xaviour l
RegisterNumber: 212223110060

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
*/
```

## Output:
![Screenshot 2024-05-16 195610](https://github.com/Tomfx03/LU-Decomposition/assets/101335832/f870bdbf-e37c-444c-abae-788cd284b681)

![Screenshot 2024-05-16 195633](https://github.com/Tomfx03/LU-Decomposition/assets/101335832/90948dda-b393-4d72-85ce-51938817a583)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

