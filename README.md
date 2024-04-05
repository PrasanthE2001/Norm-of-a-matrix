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
# Register No:212221233002
# Developed By:E Prasanth
# 1-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![Screenshot (21)](https://github.com/PrasanthE2001/Norm-of-a-matrix/assets/114572171/02f91091-482b-4e7e-8f46-9724e8dc2266)

### 2-Norm of a Matrix
![Screenshot (22)](https://github.com/PrasanthE2001/Norm-of-a-matrix/assets/114572171/c681f802-86e5-4b7c-a4f7-c8f1a8060c43)

### Infinity Norm of a Matrix
![Screenshot (23)](https://github.com/PrasanthE2001/Norm-of-a-matrix/assets/114572171/6f5cde16-3563-4ea9-a263-1afb7ac1544f)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
