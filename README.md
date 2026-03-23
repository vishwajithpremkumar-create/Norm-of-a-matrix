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
# Register No: 212225220122
# Developed By: vishwajith p
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))


# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))



# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))



```
## Output:
### 1-Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot 2026-03-23 225926" src="https://github.com/user-attachments/assets/5e9b47c7-b7c2-4368-aada-ffc14c0ca563" />

### 2-Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot 2026-03-23 225940" src="https://github.com/user-attachments/assets/7a350783-f739-42df-a65a-b878c9ff03b3" />

### Infinity Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot 2026-03-23 225954" src="https://github.com/user-attachments/assets/f98ecf85-abef-4e52-b723-adde3b6ecac0" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
