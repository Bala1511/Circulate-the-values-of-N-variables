# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
create a function circulate
### Step 2: 
enter a input of list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
fill the n: value and sum the :n value
### Step 6: 
print the values
## Program:
```
#Program to circulate N values.
#Developed by: Balamurugan
#RegisterNumber:22008625
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![output](circulateoutput.png)

## Result:
thus the experiment executed sucessfully