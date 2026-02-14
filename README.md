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
# Register No:
# Developed By:
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
<img width="1920" height="1200" alt="Screenshot 2026-02-14 082353" src="https://github.com/user-attachments/assets/27bd77d7-f77d-4164-80d0-83ab4710fc74" />


### 2-Norm of a Matrix
<img width="1920" height="1200" alt="Screenshot 2026-02-14 082410" src="https://github.com/user-attachments/assets/5f4e970f-68c4-4723-8637-7244d30ae549" />

### Infinity Norm of a Matrix

<img width="1920" height="1200" alt="Screenshot 2026-02-14 082422" src="https://github.com/user-attachments/assets/b52b44a8-0674-402b-930f-e69b03172de6" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
