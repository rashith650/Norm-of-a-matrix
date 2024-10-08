### Date:
# Ex-7 : Norm of a matrix
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
# Register No: Rashith
# Developed By: 24001082
# 1-Norm of a Matrix
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![7](https://github.com/user-attachments/assets/a5541681-f7aa-4319-8eeb-43d2ff2510b7)


### 2-Norm of a Matrix
![7 1)](https://github.com/user-attachments/assets/c2300d0f-a843-42b1-9032-9c5fd1edd14b)


### Infinity Norm of a Matrix
![7 2](https://github.com/user-attachments/assets/8cd06366-3a78-4b6e-b46f-792d4090d158)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
