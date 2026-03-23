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
<br><img width="935" height="243" alt="Screenshot 2026-03-23 104229" src="https://github.com/user-attachments/assets/c8b159d6-5c2a-4dd4-906b-43ded1e3c27c" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<br>
<br><img width="946" height="457" alt="Screenshot 2026-03-23 104156" src="https://github.com/user-attachments/assets/3b675f21-eb09-4987-9ea7-11418f52ade7" />

<br>

### Infinity Norm of a Matrix
<br>
<br><img width="957" height="428" alt="Screenshot 2026-03-23 103933" src="https://github.com/user-attachments/assets/422f0327-f123-4c1d-90f2-95e96317b6a3" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
