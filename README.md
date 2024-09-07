## DATE:

## EX:NO.4 EIGENVALUES AND EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

## Step1 : 
import numpy as np
## Step 2: 
Define the matrix 'a'
## Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4: 
Print the eigenvalues and eigenvectors


## Program:


```
#Program to find the eigen values and eigen vectors.
#Developed by: POZHILAN V D
#RegisterNumber: 212223240118

import numpy as np
a=[-2,2,-3],[2,1,-6],[-1,-2,0]
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```


## Output:
![image](https://github.com/user-attachments/assets/6d3755c6-0f2f-4be2-a6ad-75ca8d5f521b)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
