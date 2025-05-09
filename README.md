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
Python
# Register No:212224230284
# Developed By:Swetha K

# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## Output:

### 1-Norm of a Matrix

![Screenshot 2025-04-27 063752](https://github.com/user-attachments/assets/8b5e9216-4e9c-4c4d-9b1c-abd210a23d2d)
![Screenshot 2025-04-27 063803](https://github.com/user-attachments/assets/ad5c649f-d95f-4951-91df-2b128b6f3237)

### 2-Norm of a Matrix

![Screenshot 2025-04-27 063813](https://github.com/user-attachments/assets/15c4cdd6-97a0-497f-80f1-3b4e6e6fbd89)
![Screenshot 2025-04-27 063822](https://github.com/user-attachments/assets/4d7e4ee9-2a09-49b2-9ebc-e011885991d5)

### Infinity Norm of a Matrix

![Screenshot 2025-04-27 063829](https://github.com/user-attachments/assets/8748bc25-8619-4cee-8e01-eb1f65416e1c)
![Screenshot 2025-04-27 063841](https://github.com/user-attachments/assets/b254ca08-9388-4671-b5a2-55301d08c39a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
