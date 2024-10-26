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
    def circulate():
        list1=eval(input())
        count=int(input())
        for i in range(count):
            list1.append(list1[0])
            list1.pop(0)
        print("After circulating the values are:",list1)
        return
## Output:
![OUTPUT](<Screenshot 2024-10-26 182538-1.png>)

## Result:
