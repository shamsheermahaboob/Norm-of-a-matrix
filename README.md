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
# Register No:212225040400
# Developed By:Shamsheer Banu M
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```



# 2-Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix


```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix

<img width="1920" height="1200" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/6b65af27-3d17-4c1f-acb5-c7d9ea131a76" />


### 2-Norm of a Matrix

<img width="1920" height="1200" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/53cea07a-900d-47c9-9e69-b7755132708f" />

### Infinity Norm of a Matrix

![Uploading Screenshot (47).png…]()


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
