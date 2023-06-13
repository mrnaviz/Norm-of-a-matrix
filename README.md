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
Program to find the 1-Norm of a matrix.
# Register No:212222230091
# Developed By:NAVEEN KUMAR.B
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))



# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: NAVEEN KUMAR.B
RegisterNumber: 212222230091

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))



# Infinity Norm of a Matrix
Program to find Infinity norm of a matrix.
Developed by: NAVEEN KUMAR.B
Register number: 212222230091

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/mrnaviz/Norm-of-a-matrix/assets/123350791/8e46f8ac-6eb3-4aed-b67f-9fae335440a7)


### 2-Norm of a Matrix
![Screenshot 2023-06-13 192811](https://github.com/mrnaviz/Norm-of-a-matrix/assets/123350791/7a0e7297-5160-40d3-b5fb-16841e0b8fd4)


### Infinity Norm of a Matrix
![Screenshot 2023-06-13 192829](https://github.com/mrnaviz/Norm-of-a-matrix/assets/123350791/e2a0958a-65f7-4a19-8305-33d3ff99925d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
