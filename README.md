# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np.
### Step 2: 
Assign np.array() in eigen values and eigen Vectors.
### Step 3: 
Using the np.linalg.eig(),we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print both the values and vectors,then end the program.
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: E VARSHA SHARON
#RegisterNumber:22004867
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![WhatsApp Image 2023-01-03 at 2 37 50 PM](https://user-images.githubusercontent.com/111619160/210327547-c62db207-98e8-4095-94f0-e619a3059026.jpeg)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
