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
# Register No: 23012349
# Developed By: VinnushKumar L S
# 1-Norm of a Matrix
Program to find 1-norm of a matrix.
# Register No: 23012349
# Developed By: VinnushKumar L S
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
# Register No: 23012349
# Developed By: VinnushKumar L S
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
Program to find Infinity-norm of a matrix.
# Register No: 23012349
# Developed By: VinnushKumar L S
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/vinnush147/Norm-of-a-matrix/assets/147139234/6d90281d-f33f-430f-9fa4-9ec2eee0aa05)

### 2-Norm of a Matrix
![image](https://github.com/vinnush147/Norm-of-a-matrix/assets/147139234/87e11533-385b-46a1-84b3-2649b6702713)


### Infinity Norm of a Matrix
![image](https://github.com/vinnush147/Norm-of-a-matrix/assets/147139234/cda322dc-b8d1-4d60-8785-1c5a934c8bd2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
