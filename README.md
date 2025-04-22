# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```
Python
# Register No: 212224240089
# Developed By: K.Mohamed Althaf
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,1)
print("{:.2f}".format(ans))

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-22 091948](https://github.com/user-attachments/assets/80746774-9470-413c-8f50-c2b65e2fc9ae)

### 2-Norm of a Matrix
![Screenshot 2025-04-22 091024](https://github.com/user-attachments/assets/39ac9785-a54f-4bca-9578-68beec5deb41)

### Infinity Norm of a Matrix
![Screenshot 2025-04-22 091051](https://github.com/user-attachments/assets/c939fe8a-4fab-41d3-9afb-38cf27646bd3)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
