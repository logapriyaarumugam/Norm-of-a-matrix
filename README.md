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
# Register No:212225040202
# Developed By: Logapriya A
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<img width="835" height="322" alt="Screenshot 2026-11-20 091833" src="https://github.com/user-attachments/assets/eec5df30-8b48-43ce-bcf1-a6f24fe4f98c" />



### 2-Norm of a Matrix
<img width="855" height="357" alt="image" src="https://github.com/user-attachments/assets/2dd30768-9609-4893-8909-20ee53b0311a" />


### Infinity Norm of a Matrix
<img width="857" height="326" alt="image" src="https://github.com/user-attachments/assets/09260e4b-d869-44ec-9bb6-136f003428cc" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
