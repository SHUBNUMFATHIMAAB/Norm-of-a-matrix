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
# Register No: 212225240147
# Developed By:SHUBNUM FATHIMA AB

# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_norm=np.linalg.norm(matrix, 1)
print("{:.2f}".format(one_norm))

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
mnorm=np.linalg.norm(matrix, 2)
print("{:.2f}".format(mnorm))

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_norm=np.linalg.norm(matrix, np.inf)
print("{:.2f}".format(inf_norm))

```
## Output:
### 1-Norm of a Matrix
<img width="559" height="281" alt="image" src="https://github.com/user-attachments/assets/e36c6410-c0c0-4a61-813c-4b437d391c70" />

### 2-Norm of a Matrix
<img width="506" height="326" alt="image" src="https://github.com/user-attachments/assets/d30421fb-4dd5-4a5a-8726-834f0779a52e" />

### Infinity Norm of a Matrix
<img width="557" height="284" alt="image" src="https://github.com/user-attachments/assets/b8a8afb4-1641-48da-9824-901f478aeea4" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
