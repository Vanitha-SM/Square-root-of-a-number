# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Define a function.
### Step 2:
Assign number_iters = 100 in the function to perform 100 iteratios.
### Step 3:
Set i = 0.
### Step 4:
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
### Step 5:
Return number

## Program:
```
'''
program to find the square root for the given number(newton's method) using function
Developed by: Vanitha S
Register Number: 212222100057
'''
def newton(num,num_i=100):
    a=float(num)
    for i in range(num_i):
        num=0.5*(num+a/num)
    return num
a=int(input())
print("Square root of the number:",newton(a)) 

```

## Output:
![Screenshot 2023-05-10 102540](https://github.com/Vanitha-SM/Square-root-of-a-number/assets/119557985/381342ee-a076-416c-911b-269d5e81a447)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
