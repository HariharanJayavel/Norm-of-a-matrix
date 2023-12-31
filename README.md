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

# Register No: 212223240047
# Developed By: HARIHARAN J
# 1-Norm of a Matrix
```
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm = "{:.2f}".format(ans)
print(Norm)

```

# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: HARIHARAN J
RegisterNumber: 212223240047

import numpy as np


mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm = "{:.2f}".format(ans)
print(Norm)
```

# Infinity Norm of a Matrix
```
Program to find Infinity norm of a matrix.
Developed by: HARIHARAN J
RegisterNumber: 212223240047

import numpy as np


mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm = "{:.2f}".format(ans)
print(Norm)
```

## Output:
### 1-Norm of a Matrix
![image](https://github.com/HariharanJayavel/Norm-of-a-matrix/assets/144870546/e0b9a225-002c-41ec-bd24-b015dd2f5dfa)

### 2-Norm of a Matrix
![image](https://github.com/HariharanJayavel/Norm-of-a-matrix/assets/144870546/b1baf6c8-7b86-49ca-b8f4-a242f40271df)

### Infinity Norm of a Matrix
![image](https://github.com/HariharanJayavel/Norm-of-a-matrix/assets/144870546/ef228ee9-efbe-497e-b7da-2f8354bb85f9)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
