# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program.
### Step 2: 
Import the NumPy library using import numpy as np.
### Step 3: 
Create a square matrix using the np.array() function with the required elements.
### Step 4: 
Use the np.linalg.inv() function to calculate the inverse of the given matrix.
### Step 5:
Display the original matrix and its inverse using the print() statement.
### Step 6 
Stop the program.
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
b=np.linalg.inv(a)
print(b)

```
## Output:

<img width="1493" height="801" alt="image" src="https://github.com/user-attachments/assets/12726574-e188-4a8a-9b15-79716d891069" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

