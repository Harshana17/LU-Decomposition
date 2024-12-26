# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

PROGRAM 1

1.import numpy library.

2.import lu function from scipy library.

3.solve LU decomposition using lu_solve()function.

4.print the value.

PROGRAM 2

1.import numpy

2.from scipy.linalg import lu,lu_factor,lu_solve.

3.get the input of matrix values from user using eval.

4.print and solve LU decomposition using lu_solve()function.

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

