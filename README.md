# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
use the function circulate.
### Step 2: 
assign the variables in the list.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
get the result 
### Step 6: 
print the output.
## Program:
```
#Program to circulate N values.
#Developed by: DARSHAN S 
#RegisterNumber:212222100010
def circulate(): 
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
    
```

## Output:
![circulating variables](https://user-images.githubusercontent.com/115534676/230421145-583c1cef-1653-4438-aeb1-6483806d70cb.png)

## Result:
program for circulating n variables are successfully executed in python.
