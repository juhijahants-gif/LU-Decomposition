# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program and import the required library (numpy).
2.Initialize the matrix for which the LU decomposition needs to be found.
3.Apply LU Decomposition 
4.Display the results
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: JUHI JAHAN T S
RegisterNumber: 212225100020(25011334)
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: JUHI JAHAN T S
RegisterNumber: 212225100020(25011334)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
*/
```

## Output:
(i)  <img width="1206" height="470" alt="image" src="https://github.com/user-attachments/assets/b5a211ba-c0c7-4199-876a-184da45a33fa" />

(ii) <img width="921" height="210" alt="image" src="https://github.com/user-attachments/assets/a8765677-68cc-4070-9b1f-e621a2cc54ac" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

