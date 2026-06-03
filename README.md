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
# Register No: 212225240050
# Developed By: Hemavarathan S
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()),dtype=float)
l2_norm=np.linalg.norm(A,2)
print(f"{l2_norm:.2f}")

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()),dtype=float)
inf_norm=np.linalg.norm(A,np.inf)
print(f"{inf_norm:.2f}")


```
## Output:
### 1-Norm of a Matrix
<br><img width="950" height="201" alt="image" src="https://github.com/user-attachments/assets/3b15a03d-994b-4f44-a57e-c72b621c8e5a" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<br><img width="739" height="227" alt="image" src="https://github.com/user-attachments/assets/797cb2e6-3b9b-4b77-ac15-31d6755174bf" />

<br>

### Infinity Norm of a Matrix
<br>
<br>
<br><img width="772" height="197" alt="image" src="https://github.com/user-attachments/assets/f4884b09-1eb0-462c-816e-fb0f2dd7f8af" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
