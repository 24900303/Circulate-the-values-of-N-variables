# Date :
# Exp no :2
# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
### Step 2: 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
### Step 6: 
## Program:
# Developed by:Rudesh kanna R
# Register no:24900303
def circulate():
    global lst,n
    n = n % len(lst)
    rotated_list = lst[n:] + lst[:n]
    print(f"After circulating the values are: {rotated_list}")
lst=list(eval(input()))
n = int(input())
## Output:
![image](https://github.com/user-attachments/assets/7cd02a39-71d4-4d17-9359-31a42233fdfe)

## Result:
The output for circulate the values of n variables is successfull.

