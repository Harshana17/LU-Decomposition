# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print'

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable

4.print the variable 'X' 

## Program:
(i) To find the L and U matrix




Program to find the L and U matrix.
Developed by:Harshana M V 
RegisterNumber:24002128


```

import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)

```

(ii) To find the LU Decomposition of a matrix


Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 


```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)

```

## Output:
![OUTPUT1](<Screenshot 2024-11-26 101952-2.png>)
![OUTPUT2](<Screenshot 2024-11-26 102027-2.png>)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

