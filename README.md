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

## Program:``
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: NARESH.R
RegisterNumber:23005559  
*/
def square_root_newton(number):
    x = number/2.0
    iterations= 100
    for _ in range (iterations):
        x = 0.5*(x+number/x)
    return x
a = int(input())
result= square_root_newton(a)
print("Square root of the number:",result)
```

## Output:
![Screenshot 2023-11-28 110541](https://github.com/feryjfgkuyfgewjfgew/Square-root-of-a-number/assets/150319377/2cf75871-2ade-4d9b-84f7-8f2f688edcd8)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
