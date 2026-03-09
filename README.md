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
<img width="1920" height="1200" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/efbcaacd-7315-4489-b319-9a00b50f94e5" />


### 2-Norm of a Matrix
<img width="1920" height="1200" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/c8ed2587-148e-44c9-ac2a-492e7fb7d9b2" />



### Infinity Norm of a Matrix
<img width="1920" height="1200" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/e08bdcf6-55ba-491b-a2ce-552e56d49715" />




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
