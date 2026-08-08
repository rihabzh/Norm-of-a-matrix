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

<img width="746" height="697" alt="Screenshot 2026-08-08 150654" src="https://github.com/user-attachments/assets/df60afab-2d43-4db6-ae7a-d547c505fe1f" />

### 2-Norm of a Matrix
<img width="968" height="757" alt="Screenshot 2026-08-08 150704" src="https://github.com/user-attachments/assets/e6210288-4ee7-4fd9-b2c3-8c92e9f209a9" />


### Infinity Norm of a Matrix
<img width="726" height="686" alt="Screenshot 2026-08-08 150712" src="https://github.com/user-attachments/assets/7e0c030f-d4a1-416e-a2e3-f3b1ba063272" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
