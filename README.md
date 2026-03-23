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
# Register No:212225240085
# Developed By:MOHAMED SAUDH R
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)


# 2-Norm of a Matrix

import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))



```
## Output:
### 1-Norm of a Matrix
<img width="935" height="243" alt="Screenshot 2026-03-23 104229" src="https://github.com/user-attachments/assets/4161a305-a68e-4899-9c5d-83a661db0eb0" />

<br>

### 2-Norm of a Matrix
<img width="946" height="457" alt="Screenshot 2026-03-23 104156" src="https://github.com/user-attachments/assets/716aeeaf-7c35-429b-9fd7-f62f6fce92b5" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="957" height="428" alt="Screenshot 2026-03-23 103933" src="https://github.com/user-attachments/assets/70d2acbf-d63c-4426-9885-408a1526eed1" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
