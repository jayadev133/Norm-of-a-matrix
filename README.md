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
# Register No: 212223240058
# Developed By: JAYADEV PALLINTI
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```


# 2-Norm of a Matrix
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
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
![Screenshot 2023-12-25 163022](https://github.com/jayadev133/Norm-of-a-matrix/assets/150319465/bf2f342b-334e-4a3f-9356-ce0c53dfb88d)



### 2-Norm of a Matrix
![Screenshot 2023-12-25 163102](https://github.com/jayadev133/Norm-of-a-matrix/assets/150319465/f39ae3df-db93-4267-b09e-6aad8daa270b)


### Infinity Norm of a Matrix
![Screenshot 2023-12-25 163127](https://github.com/jayadev133/Norm-of-a-matrix/assets/150319465/44095769-6560-4d41-ab7f-f3603e24a88b)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
