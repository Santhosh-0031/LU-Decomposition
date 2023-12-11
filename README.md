# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy and scipy.linalg libraries
2. Accept user input for the matrix
3. Perform LU decomposition
4. Print the lower and upper triangular matrices

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: santhosh kumar R
RegisterNumber: 23013562

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U= lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: santhosh kumar R
RegisterNumber: 23013562

import numpy as np
from scipy.linalg import lu ,solve
A = np.array(eval(input()))
B = np.array(eval(input()))
P,L,U= lu(A)
y=solve(L, np.dot(P,B))
x=solve(U,y)
print(x)


*/
```

## Output:
#### LU decomposition find L and U

![Alt text](<Screenshot 2023-12-11 092421-1.png>)

#### LU decomposition solve the matrix

![Alt text](<Screenshot 2023-12-11 092724.png>)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

