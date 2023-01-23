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
![Screenshot from 2023-01-23 23-12-03](https://user-images.githubusercontent.com/118749665/214111085-f3fb2f44-dd7f-403e-95bd-2cab5c6b55ae.png)

## Result:
Thus the circulation of n variables are successfully executed
