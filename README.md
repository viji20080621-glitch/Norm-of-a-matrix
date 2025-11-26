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
# Register No:25017569
# Developed By:VIJIYALAKSHMI A
```
## 1-Norm of a Matrix

```
import numpy as np
A = np.array(eval(input()))
norm1 = np.linalg.norm(A,1)
print(f"{norm1:.2f}")

```

## 2-Norm of a Matrix

```
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")

```

## Infinity Norm of a Matrix

```
import numpy as np
A=np.array(eval(input()))
norm3=np.linalg.norm(A,np.inf)
print(f"{norm3:.2f}")

```
## Output:
### 1-Norm of a Matrix

<img width="1235" height="443" alt="Screenshot 2025-11-26 112348" src="https://github.com/user-attachments/assets/a1facb10-61d3-4f4c-8861-5943bab09604" />
<img width="1239" height="235" alt="Screenshot 2025-11-26 112406" src="https://github.com/user-attachments/assets/5aa365d0-4c3f-4959-9fdb-3d5fb53ab8eb" />

### 2-Norm of a Matrix

<img width="1238" height="652" alt="Screenshot 2025-11-26 112449" src="https://github.com/user-attachments/assets/78e89942-3229-412c-8126-276b841af7f9" />
<img width="1237" height="282" alt="Screenshot 2025-11-26 112508" src="https://github.com/user-attachments/assets/c4098c76-0311-40da-844f-4b0431cba753" />

### Infinity Norm of a Matrix

<img width="1232" height="409" alt="Screenshot 2025-11-26 112525" src="https://github.com/user-attachments/assets/7d29cbdd-f2b3-4bb6-9754-476fb0e80517" />
<img width="1241" height="235" alt="Screenshot 2025-11-26 112539" src="https://github.com/user-attachments/assets/567d915f-a375-4647-9822-a1bf3f602e1f" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
