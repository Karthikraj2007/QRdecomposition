# Algorithm for QR Decomposition
## Aim:
To implement QR decomposition algorithm using the Gram-Schmidt method.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Intialize the matrix Q and u
2.	The vector u and e is given by

    ![eqn1](./ex4.jpg)

    ![eqn2](./ex6.jpg)

    ![eqn3](./ex3.jpg)

3.	Obtain the Q matrix   
    ![eqn4](./ex1.jpg)
4.	Construct the upper triangular matrix R
    ![eqn5](./ex2.jpg)



## Program:
### Gram-Schmidt Method
```
Program to find 2-norm of a matrix.
Developed by: Karthikraj C
RegisterNumber: 212224230117

import numpy as np
matrix=np.array(eval(input()))
res=np.linalg.norm(matrix,2)
print("{:.2f}".format(res))
```

## Output
![alt text](<Screenshot 2025-05-21 235046.png>)

## Result
Thus the QR decomposition algorithm using the Gram-Schmidt process is written and verified the result.