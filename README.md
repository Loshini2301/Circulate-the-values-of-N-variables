# Circulate-the-values-of-N-variables
## NAME:LOSHINI G
## REGISTER NO:212223220051
## DEPARTMENT:IT
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Start the program.

### Step 2:
Define a function named circulate().

### Step 3:
Get the list of values and the number of rotations from the user.

### Step 4:
Using the slicing concept, rotate the list to the left by the given number of times.

### Step 5:
Print the circulated list.

### Step 6:
End the program.


## Program:
```
#Program to circulate N values.
#Developed by: Loshini G
#RegisterNumber:23012268
def circulate():
    list1=eval(input())
    a=int(input())
    l2=[]
    for i in range(a,len(list1)):
        l2.append(list1[i])
    for i in range(a):
        l2.append(list1[i])
    print("After circulating the values are:",l2)
```  

## Output:
![ex 2 ans](https://github.com/user-attachments/assets/0fde98ba-623a-4c8d-960e-6a1cd7d188e4)

![ex 2 op](https://github.com/user-attachments/assets/cae810b2-5e2c-4da0-af68-acce8b684e34)


## Result:
Thus the program executed successfully
