# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu
3. Assign the values
4. Note the output

## Program:
```
Developed By: Sivaramkrishnan B
Register Number: 212222110044
```
(i) To find the L and U matrix

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
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu, piv = lu_factor(A)
x= lu_solve((lu,piv),B)
print(x)

```
## Program Statement:

### (i) To find the L and U matrix
![Screenshot 2023-06-14 141254](https://github.com/SivaramakrishnanBaskar/LU-Decomposition/assets/119476322/4384f07a-fe1c-4b6b-a1e1-b8ee54efdd8f)

### (ii) To find the LU Decomposition of a matrix
![Screenshot 2023-06-14 141535](https://github.com/SivaramakrishnanBaskar/LU-Decomposition/assets/119476322/8235f8b1-eb1f-4686-ad0a-85060818d38f)


## Output:
### (i) To find the L and U matrix
![image](https://github.com/SivaramakrishnanBaskar/LU-Decomposition/assets/119476322/2f4e0d25-5d3a-425f-9617-0eebae071f05)

### (ii) To find the LU Decomposition of a matrix
![Screenshot 2023-06-14 141958](https://github.com/SivaramakrishnanBaskar/LU-Decomposition/assets/119476322/67f77106-ce93-42b3-932f-3fd9b6c061da)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
