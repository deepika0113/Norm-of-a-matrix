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

# Register No:212224100009
# Developed By:DEEPIKA.R
# 1-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
res=np.linalg.norm(a,1)
print(res)
```



# 2-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
res=np.linalg.norm(a,2)
print("{:.2f}".format(res))
```




# Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
res=np.linalg.norm(a,np.inf)
print("{:.2f}".format(res))
```
## Output:
### 1-Norm of a Matrix
<img width="1161" height="963" alt="Screenshot 2025-09-19 111225" src="https://github.com/user-attachments/assets/0682b0de-1907-4567-9af7-f77bef8c59b3" />

### 2-Norm of a Matrix
<img width="1126" height="949" alt="Screenshot 2025-09-19 111208" src="https://github.com/user-attachments/assets/f2e354a4-840d-4850-8e48-31110df026d8" />

### Infinity Norm of a Matrix
<img width="991" height="944" alt="Screenshot 2025-09-19 111239" src="https://github.com/user-attachments/assets/fac48302-ae91-41bd-8467-14e215fcc5b6" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
