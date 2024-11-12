# Exp no :2
# Date :
# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Get the values from the user

### Step 2:
Assign the value of variable to a temporary variable

### Step 3:
Get the value from the user for the number of rotation

### Step 4:
Using the slicing concept rotate the list

### Step 5:
Print both the values it would be interchanged

### Step 6:
End the program
## Program:
```
Developed by:RUDESH KANNA R
Register no:24900303


def circulate():
    global lst,n
    n = n % len(lst)
    rotated_list = lst[n:] + lst[:n]
    print(f"After circulating the values are: {rotated_list}")
lst=list(eval(input()))
n = int(input())
```
### Output:
![image](https://github.com/user-attachments/assets/9b9ed95b-bb1f-44d9-9cf8-bf94e346d523)

## Result:
The output for circulate the values of n variables is successfull.

