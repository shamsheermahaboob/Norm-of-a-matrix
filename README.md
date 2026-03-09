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
<img width="1920" height="1200" alt="Screenshot (50)" src="https://github.com/user-attachments/assets/cd7cbb95-c4fc-4c0d-a4b8-fc336825b415" />



### 2-Norm of a Matrix

<img width="1920" height="1200" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/f958f08c-a24c-42cd-9b55-695939ad7f73" />


### Infinity Norm of a Matrix
<img width="1920" height="1200" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/6710e63f-6606-4583-905d-da3e2f4545bf" />





## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
