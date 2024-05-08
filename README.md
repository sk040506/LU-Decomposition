## LU Decomposition
## AIM:
To write a program to find the LU Decomposition of a matrix.
## Equipments Required:
Hardware – PCs

Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm :
1.Read the elements of augmented matrix into arrays a and b

2.Calculate elements of L and U

3.Print elements of L and U

4.Find V by solving LV = B by forward substitution

5.Find X by solving UX = V by backward substitution

6.Print Array X as the solution
## Program:
(i) To find the L and U matrix
```
#Developed by : sk balaji
#Register Number : 2305003001

import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix

Program to find the LU Decomposition of a matrix.
```
#Developed by : sk balaji
#Register Number : 2305003001

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A= np.array(eval(input()))
B= np.array(eval(input()))
lu, ply = lu_factor(A)
x= lu_solve((lu,ply),B)
print(x)
```
## Output:
![image](https://github.com/sk040506/LU-Decomposition/assets/155505137/4ebe4746-2309-436e-b101-eeec6a5baa75)
![image](https://github.com/sk040506/LU-Decomposition/assets/155505137/42ec71f6-fcfc-4ff3-97a9-5aba18eb54ec)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.


