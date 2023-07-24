# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
create a function name circulate()
### Step 2: 
get a list as input from user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the list
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: MIDHUN S
#RegisterNumber:23003250
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![output](/Screenshot%202023-07-24%20074755.jpg)

## Result:
Thus the program to find the circulate N values is written and verified using python programming.