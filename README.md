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

# 1-Norm of a Matrix
```
'''
developed by : RIHAB ZAKKAIR HUSSAIN
REGISTRATION NO: 212225230226
'''

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
m=np.array(eval(input()))
r=np.linalg.norm(m,1)
print(r)
```



# 2-Norm of a Matrix
```
'''
developed by : RIHAB ZAKKAIR HUSSAIN
REGISTER NO: 212225230226
'''

import os 
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
m=np.array(eval(input()))
r=np.linalg.norm(m,2)
print(f"{r:.2f}")
```



# Infinity Norm of a Matrix
```
'''
developed by : RIHAB ZAKKAIR HUSSAIN
REGISTER NO: 212225230226
'''

import os 
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
m=np.array(eval(input()))
r=np.linalg.norm(m,np.inf)
print(f"{r:.2f}")
```


## Output:
### 1-Norm of a Matrix

<img width="887" height="721" alt="Screenshot 2026-08-08 143608" src="https://github.com/user-attachments/assets/40853298-7898-4bbf-8597-70d02b230b1e" />

### 2-Norm of a Matrix
<img width="673" height="541" alt="Screenshot 2026-08-08 143615" src="https://github.com/user-attachments/assets/c3003645-17a5-447b-9404-437db3689174" />


### Infinity Norm of a Matrix
<img width="652" height="722" alt="Screenshot 2026-08-08 150210" src="https://github.com/user-attachments/assets/c0c96900-2c18-457b-8379-fee8e04dbdfe" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
