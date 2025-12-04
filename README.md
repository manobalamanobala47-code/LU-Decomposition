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
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: R.Manobala
RegisterNumber: 25016414
'''
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
'''Program to solve a matrix using LU decomposition.
Developed by: R.Manobala
RegisterNumber:25016414 
'''

# To print X matrix (solution to the equations)
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


<img width="1920" height="1080" alt="Screenshot 2025-11-19 143631" src="https://github.com/user-attachments/assets/c85dbdd4-91fe-4910-bb00-0b53d0c09d02" />

<img width="1920" height="1080" alt="Screenshot 2025-11-19 143647" src="https://github.com/user-attachments/assets/b4b11f4e-da72-4b0b-a9e0-592766d39e55" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

