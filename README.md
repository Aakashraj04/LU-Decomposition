# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

(i) To find the L and U matrix 

Step 1:
Import numpy and scipy from the python library.

Step 2:
Get the input from the user in array format.

Step 3:
Calculate L and U matrix using lu() builtin function.

Step 4:
Print the L matrix and U matrix.

Step 5:
End the program.

## Program:
```
#Program to find the L and U matrix.
Developed by: Aakashraj M 
RegisterNumber: 22008579 

import numpy as np
from scipy.linalg import lu
ar=eval(input())
a=np.array(ar)
P,L,U=lu(a)
print(L)
print(U)
```

Output:
![L and U matrix output](https://user-images.githubusercontent.com/121117266/212457559-51730331-b9fe-47b0-97b9-53d3da741172.png)


#Algorithm

(ii) To find the LU Decomposition of a matrix

Step 1:
Import numpy and scipy from the python library.

Step 2:
Get the input from the user and arrange in array format.

Step 3:
To calculate the solution of the given matrix use lu_factor() and lu_solve() builtin function.

Step 4:
Print the final solution.

Step 5:
End the program.


#Program
```
#Program to find the LU Decomposition of a matrix.
Developed by: Aakashraj M
RegisterNumber: 22008579

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=eval(input())
res=lu_factor(a)
soln=lu_solve(res,b)
print(soln)

```

## Output:
![image](https://user-images.githubusercontent.com/121117266/212457718-a659b7ad-5444-4aa4-a23c-c83808dc2877.png)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

