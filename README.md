# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: ATCHAYA B
RegisterNumber: 212224220015
*/
```
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: ATCHAYA B
RegisterNumber: 212224220015
*/
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```


## Output:

(i) To find the L and U matrix

<img width="952" height="780" alt="image" src="https://github.com/user-attachments/assets/cf8e1e31-55b6-418d-b3e5-f2d64080c5c5" />

(ii) To find the LU Decomposition of a matrix

<img width="750" height="617" alt="image" src="https://github.com/user-attachments/assets/828fd4c8-ca89-40eb-b8dd-ddfa20cc5fa5" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

