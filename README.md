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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
        



```
## Output:

![Screenshot (58)](https://github.com/user-attachments/assets/4025f6a2-8efa-48fe-bd7d-80c5c6f19aa2)
![Screenshot (59)](https://github.com/user-attachments/assets/7d8abee5-331c-4d1e-84ac-dd808a500abb)
![Screenshot (60)](https://github.com/user-attachments/assets/0dd17126-f4dd-4541-80eb-990cf4fd7c87)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
