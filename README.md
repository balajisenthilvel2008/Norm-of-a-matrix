# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 1-norm,2-norm, and infinity norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 25012884
# Developed By: Balaji S
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
print(b)

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
print(round(b,2))

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(b)
```

## Output:
### 1-Norm of a Matrix
<img width="819" height="775" alt="image" src="https://github.com/user-attachments/assets/191c650f-ba76-4aa8-b9c3-3af97cf6d823" />

### 2-Norm of a Matrix
<img width="818" height="789" alt="image" src="https://github.com/user-attachments/assets/3f82c349-ed02-4851-ac14-bca026daded3" />

### Infinity Norm of a Matrix
<img width="834" height="800" alt="image" src="https://github.com/user-attachments/assets/3aa52678-c931-4947-9785-e397351e0449" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
