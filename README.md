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
# Register No:212225040175
# Developed By:karthiga sr.G
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
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
<img width="1497" height="857" alt="image" src="https://github.com/user-attachments/assets/3450e1e2-6134-481a-aa22-025a19c5f07f" />
### 2-Norm of a Matrix
<img width="1548" height="894" alt="image" src="https://github.com/user-attachments/assets/105eaf5f-2dec-4687-b99a-f1d50dcebedd" />
### Infinity Norm of a Matrix
<img width="1562" height="825" alt="image" src="https://github.com/user-attachments/assets/ed5985b6-96a4-42cd-a967-5212af46d689" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
