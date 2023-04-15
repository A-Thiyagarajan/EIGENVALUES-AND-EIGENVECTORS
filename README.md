# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :

Import the numpy module to use the built-in functions for calculation.
### Step 2:

Prepare the lists from each equations and assign in np.array()
### Step 3:

Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:

End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: A.Thiyagrajan
#RegisterNumber:212222240110
import numpy as np
A=np.array([[4,2],[2,4]])
evaluate,evector=np.linalg.eig(A)
print("Eigen values are {0} and Eigen Vectors are {1}".format(evaluate,evector))
```

## Output:
![eigen](https://user-images.githubusercontent.com/118707693/226388130-8c6f9c31-6da2-40a5-9cca-90001333f426.png)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
