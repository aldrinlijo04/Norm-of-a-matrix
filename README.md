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
## NORM_OF_A_MATRIX
```
 Developed By: Aldrin Lijo J E
 Ref no: 22008844
 1-Norm of a Matrix
```
```Python
import numpy as np 
mat = np.array(eval(input())) 
ans = np.linalg.norm(mat,1)
Norm_of_matrix ="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

![1-norm](/Screenshot%202023-01-18%20055317.png)
![1-norm](/Screenshot%202023-01-18%20055418.png)

### 2-Norm of a Matrix

![2-norm](/2-norm.png)
![2-norm](/2-norm%20output.png)

### Infinity Norm of a Matrix

![Infinitynorm](/infin.png)
![Infinitynorm](/infin%20output.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
