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
# Register No:212225240493
# Developed By:Vishal-R
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
<img width="1323" height="914" alt="Screenshot 2026-03-25 213824" src="https://github.com/user-attachments/assets/e9c93a8f-3a74-4dad-b9b0-070c157d9966" />
<img width="1311" height="895" alt="Screenshot 2026-03-25 214034" src="https://github.com/user-attachments/assets/549e6b2c-2160-4231-bc52-c0d5f38331a2" />
<img width="1238" height="855" alt="Screenshot 2026-03-25 214155" src="https://github.com/user-attachments/assets/eb0be8dc-2327-41c2-919a-cbca9b1f196e" />

### 1-Norm of a Matrix
<br>
<br>
<br>

### 2-Norm of a Matrix
<br>
<br>
<br>

### Infinity Norm of a Matrix
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
