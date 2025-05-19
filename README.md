# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

(i)

1.Import numpy as np and from scipy.linalg import lu

2.using np.array store matrix in variable matrix

3.using lu(),we can find lower triangular matrix and upper triangular matrix

4.print the lower triangular matrix and upper triangular matrix

(ii)

1.import numpy as np and from scipy.linalg import lu

2.using np.array store matrix in variable matrix

3.using lu_solve( ) the LU decomposition of matrix can be found

4.using lu_solve(), we can find the solution

5.print the solution

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 212224100034
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
Developed by: 
RegisterNumber:212224100034

*/
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
![lu decomposition]()

![Screenshot (98)](https://github.com/user-attachments/assets/4f74883d-1bba-48d5-84ed-2adcb23d0978)
![Screenshot (99)](https://github.com/user-attachments/assets/fa1e3ff6-4a2c-4e6f-814c-fad75e87bf59)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

