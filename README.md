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
```
'''
register number:212225040497
name: vivek christo A
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Infinity Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```




## Output:
### 1-Norm of a Matrix
<img width="523" height="126" alt="Screenshot 2026-02-07 085022" src="https://github.com/user-attachments/assets/00579ec4-9541-4064-b027-3f9f3cddd205" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="484" height="195" alt="Screenshot 2026-02-07 085043" src="https://github.com/user-attachments/assets/a9da4d35-4c5c-40f4-8161-6a7de59fba73" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="563" height="171" alt="Screenshot 2026-02-07 085102" src="https://github.com/user-attachments/assets/f673e402-623e-4c36-b544-b594b7fceeda" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
