# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212222230016
# Developed By: BALAMURUGAN B
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 3-Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![MAI 1NORM](https://github.com/BALA291/Norm-of-a-matrix/assets/120717501/c773a3ff-244c-46c8-9e48-10a5cc96e337)

<br>

### 2-Norm of a Matrix
![Mai 2norm](https://github.com/BALA291/Norm-of-a-matrix/assets/120717501/4da1bd3f-fc4d-4549-8821-329f0a293345)

<br>

### 3-Infinity Norm of a Matrix
![MAI INFNORM](https://github.com/BALA291/Norm-of-a-matrix/assets/120717501/63f44ff0-b7a2-4fa6-ae92-45feb6fbdaf6)

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
