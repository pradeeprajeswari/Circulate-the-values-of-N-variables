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

!["Output"]![swapcirculate png](https://github.com/pradeeprajeswari/Circulate-the-values-of-N-variables/assets/145743112/135d2473-6f9a-4a26-a2c4-4c3f8cc6c09a)


## Result:
Thus the python for Circulate the values of n variables is executed successfully

