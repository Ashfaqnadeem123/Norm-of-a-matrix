# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Get the input matrix using np.array()   
### Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
### Step 3:
Print the norm of the matrix in two decimal places.
### Step 4:
End the program.
## Program:
```Python
# Register No:212224230166
# Developed By:MOHAMMED ASHFAQ NADEEM A
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.

'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.

'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)
# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.

'''
import numpy as np
mat = np.array(eval(input()))
norm = np.linalg.norm(mat,ord=np.inf)

print('{:.2f}'.format(norm))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-05-21 083727](https://github.com/user-attachments/assets/c59b713a-ef80-44b1-a7b6-0284f0f2a5fe)

### 2-Norm of a Matrix
![Screenshot 2025-05-21 083736](https://github.com/user-attachments/assets/85ab6dec-3556-4807-98ca-ebef7b3799ce)

### Infinity Norm of a Matrix
![Screenshot 2025-05-21 083743](https://github.com/user-attachments/assets/6052ed3b-1c61-46c6-8b11-3c9ae4adfda2)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
