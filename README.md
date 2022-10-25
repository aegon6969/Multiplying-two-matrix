# Multiplying-two-matrix

## AIM:
To write a python program for multiplying two matrix.

## ALGORITHM:

### Step 1: 
Import Numpy as np.
### Step 2: 
Get input from the user.
### Step 3: 
Create empty lists l1 and l2.
### Step 4: 
Use for loop to append the values into the list created.
### Step 5: 
Print the product of two arrays.

## PROGRAM: 
```PYTHON
To write a python program for multiplying two matrix.
Developed By: M.Rishi
Register Number: 22000276
import numpy as np
n=int(input())
l1=[]
l2=[]
for i in range(n):
    l1.append(int(input()))
for j in range(n):
    l2.append(int(input()))
array1=np.array(l1)
array2=np.array(l2)
prod=array1*array2
print("Product of two arrays is:",prod)
```

## OUTPUT:
![OUTPUT](/muti.png)

## RESULT:
Thus the program is written to multiply two matrix.

