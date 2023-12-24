# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
```
1.import the numpy as np
2.from scipy.linalg import lu
3.enter the lists from each linear equationa and assgin in np.array()
4.using lu( )and store it in three variables
5.print the L and U matrix
6.end the program
```
## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Tirupathi Jayadeep
RegisterNumber: 23004426
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
Developed by: Tirupathi Jayadeep
RegisterNumber: 23004426

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
 

```

## Output:
![Screenshot 2023-12-24 094519](https://github.com/23004426/LU-Decomposition/assets/144979327/a8f2f21c-3aed-4c14-93da-3af64673a7a9)
![Screenshot 2023-12-24 094540](https://github.com/23004426/LU-Decomposition/assets/144979327/b78204a8-69ff-4e2f-830a-7c15e260061d)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

