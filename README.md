# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm (i)
1.Import numpy and scipy.linalg,in linalg you can input lu. and in second program can import lu_factor and lu_solve from python library as same as in second program.

2.Get the input from user as the form of nested list to compute numpy array format.

3.Use inputted array (matrix) to compute in corresponding builtin modules function such as lu and create new variables such as piv,i matrix u matrix to store.

4.Print the corresponding bvariable to get output (I_matrix)

5.Print the corresponding bvariable to get output (u_matrix)


# Algorithm (ii)
1.In second program can import lu_factor and lu_solve from python library as same as in second program.

2.Get the input from user in the form of nested list to compute numpy array format and declare it for both the variables.

3.Create the varaiable to Use inputted array to compute of lu_factor of matrix varaible

4.Create the new variable for lu_solve to compute of 'x' varaiable and 'b' variable

5.Print the corresponding variable (solution) to get output
 
 ## Program:
(i) To find the L and U matrix
Program to find the L and U matrix.
Developed by: BUSHPIKA C
RegisterNumber: 212225230038
```
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```

(ii) To find the LU Decomposition of a matrix

Program to find the LU Decomposition of a matrix.
Developed by: BUSHPIKA C
RegisterNumber: 212225230038 
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
<img width="1215" height="582" alt="image" src="https://github.com/user-attachments/assets/33cb91c7-90d1-4428-978f-3704db6d83a7" />
<img width="1252" height="328" alt="image" src="https://github.com/user-attachments/assets/c96d8340-1895-4918-9aed-efc10755dc86" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

