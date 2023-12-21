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
# Register No:23003922
# Developed By:Ekkaluri Mythri
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/mythriekkaluri2005/Norm-of-a-matrix/assets/150231422/b23bed1d-798e-4931-af79-a95989f0f972)

### 2-Norm of a Matrix
![image](https://github.com/mythriekkaluri2005/Norm-of-a-matrix/assets/150231422/dc02c24e-894d-4b63-8887-1f7c1373f975)


### Infinity Norm of a Matrix
![image](https://github.com/mythriekkaluri2005/Norm-of-a-matrix/assets/150231422/8f00f79c-a33b-458e-8b3d-2e09bbfd47d9)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
