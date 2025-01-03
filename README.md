# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu
3. get input as np.array()
4. now use the lu() and print the  output
## Program:
```
(i) To find the L and U matrix

/*
import numpy as nu 
from scipy.linalg import lu 
a=nu.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

Developed by: k rahul royal
RegisterNumber: 24001378
*/

(ii) To find the LU Decomposition of a matrix

/*
import numpy as np
from scipy.linalg import lu_factor,lu_solve 
a=eval(input())
b=eval(input())
a=np.array(a)
b=np.array(b)
result=lu_factor(a)
sol=lu_solve(result,b)
print(sol)

Developed by: k rahul royal
RegisterNumber: 24001378
*/
```

## Output:
![alt text](<Screenshot 2024-12-25 145352.png>)
![alt text](<Screenshot 2024-12-25 145410.png>)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

