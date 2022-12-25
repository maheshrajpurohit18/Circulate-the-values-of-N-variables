# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
create a function called Circulate
### Step 2: 
create two variables and ask the values
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
After, give the print statement
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: mahesh raj purohit
#RegisterNumber:22008605
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![output](/Screenshot%20from%202022-12-25%2022-15-58.png)
## Result:
Thus the circulation of n variables are successfully executed