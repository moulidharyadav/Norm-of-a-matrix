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
# Register No:23009285
# Developed By:MOULIDHAR.G
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: MOULIDHAR.G
RegisterNumber: 23009285
'''
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:MOULIDHAR.G
RegisterNumber: 23009285
'''
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix
'''
Program to find infinity-norm of a matrix.
Developed by: MOULIDHAR.G
RegisterNumber: 23009285
'''
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/moulidharyadav/Norm-of-a-matrix/assets/147078316/1b897fc5-e35b-4223-a474-8e125c7eaa33)


### 2-Norm of a Matrix
![image](https://github.com/moulidharyadav/Norm-of-a-matrix/assets/147078316/16017c2b-3c75-4e95-8e91-506aad1ca8e5)


### Infinity Norm of a Matrix
![image](https://github.com/moulidharyadav/Norm-of-a-matrix/assets/147078316/d7752c03-6961-4934-bcf4-d4ebe2dd8b5e)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
