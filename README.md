# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user for list variable 'l'
### Step 2:
Get the value from the user for the number of rotation
### Step 3: 
Then define a function with function name circulate
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
Print the values of list variable 'l', outside the function using functioncall after circulating variables
### Step 6:
End the program 

## Program:
```
#Program to circulate N values.
#Developed by:Shaik Shoaib Nawaz
#RegisterNumber:22005600
l=eval(input())
n=int(input())
def circulate():
    n1=l[n:]+l[:n]
    return n1
print("After circulating the values are:",circulate())
```
## Output:
!["Output"](/output2.png)

## Result:
Thus the circulation of n variables is successfully executed

