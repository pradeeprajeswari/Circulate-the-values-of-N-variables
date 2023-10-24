# CIRCULATE THE VALUES OF N VARIABLES
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Using concatination operatoin display the entire rotated list
### Step 6: 
Stop the program
## Program:
```
#Program to circulate N values.
#Developed by: Pradeep.E
#RegisterNumber:23013416
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)

```
## Output:!

![circuatetwo values png](https://github.com/pradeeprajeswari/Circulate-the-values-of-N-variables/assets/145743112/1bfb4e7a-0f81-477e-8eed-61aed00385c7)


## Result:
Thus the python for Circulate the values of n variables is executed successfully

