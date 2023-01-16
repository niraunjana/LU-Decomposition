# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np
2. Assign in np.array()
3. Using the np.linalg.solve(),we can find the solutions.
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: NIRAUNJANA GAYATHRI G R
RegisterNumber: 22008369import numpy as np
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
Developed by: NIRAUNJANA GAYATHRI G R
RegisterNumber: 22008369

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
```

## Output:
file:///home/sec/Pictures/Screenshots/Screenshot%20from%202023-01-16%2016-10-48.png![image](https://user-images.githubusercontent.com/119395610/212660528-51f92f76-e00c-4b88-803d-38c8613b9c71.png)
file:///home/sec/Pictures/Screenshots/Screenshot%20from%202023-01-16%2016-18-56.png![image](https://user-images.githubusercontent.com/119395610/212660717-c21f366f-4646-4c89-a7e7-b96056340d59.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

