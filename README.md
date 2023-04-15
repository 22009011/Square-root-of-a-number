# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```

Program to find the square root for the given number(newton's method) using function.
Developed by: Thanjiyappan.k
RegisterNumber:  212222240108

def newton_method(n1,n2=100):
    a=float(n1)
    for i in range(n2):
        n1=0.5*(n1+a/n1)
    return n1
a=int(input())    
print("Square root of the number:",newton_method(a))


```

## Output:
![Screenshot 2023-04-15 at 15-59-53 Exp-2b-CR- Square root of a number Attempt review](https://user-images.githubusercontent.com/118343461/232208724-684d4b07-77e7-4d0e-b23b-e0fe82ad9521.png)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
