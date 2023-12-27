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
# Register No: 23000080
# Developed By: TAMILARASAN K S.
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)



# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)


# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom) 



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-27 084033](https://github.com/KSTamilarasan17/Norm-of-a-matrix/assets/138849236/b44da302-a8a0-40e3-9f4d-a834676283ad)


### 2-Norm of a Matrix
![Screenshot 2023-12-27 084049](https://github.com/KSTamilarasan17/Norm-of-a-matrix/assets/138849236/9ad2d9bf-3dab-473b-a103-0ff8af86cf5e)


### Infinity Norm of a Matrix
![Screenshot 2023-12-27 084059](https://github.com/KSTamilarasan17/Norm-of-a-matrix/assets/138849236/61627c79-0439-464e-a48e-f2e47ad38df7)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
