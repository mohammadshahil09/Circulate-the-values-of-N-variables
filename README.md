# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
Get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
using concatenation operation display the entire rotated list
### Step 6: 
stop the  program
## Program:
```
#Program to circulate N values.
#Developed by:guntur shaik mohammad shahil
#RegisterNumber:23011002
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
  ```  
## Output:
![Screenshot 2023-10-29 163857](https://github.com/mohammadshahil09/Circulate-the-values-of-N-variables/assets/145742840/9f3b36fb-306d-42a4-af3c-5ab570d51b6f)

## Result:
