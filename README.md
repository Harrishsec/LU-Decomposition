# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step 1: Start the program.

### Step 2: Import the required libraries numpy and scipy.linalg.

### Step 3: Read the elements of the matrix from the user and store them in a matrix form.

### Step 4: Use the lu() function from scipy.linalg to decompose the matrix into Lower (L) and Upper (U) triangular matrices.

### Step 5: Display the matrices L and U.

### Step 6: Stop the program.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Harrish P
RegisterNumber: 212224230088
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Harrish P
RegisterNumber: 212224230088
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
l,p=lu_factor(A)
x=lu_solve((l,p),B)
print(x)
```

## Output:
<img width="1910" height="1049" alt="image" src="https://github.com/user-attachments/assets/750cb601-b1e9-448a-b2df-3a186deee234" />
<img width="1917" height="1049" alt="image" src="https://github.com/user-attachments/assets/c24c9989-841d-4a97-8b44-f66f0d2b3a86" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

