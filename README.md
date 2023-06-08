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
Developed by: ANANDHAMOORTHY.K
RegisterNumber: 212222100004
def network_method(number,number_iters = 100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",network_method(a))
```

## Output:
![Screenshot 2023-06-08 120702](https://github.com/AnandhamoorthyKarthikeyan/Square-root-of-a-number/assets/119475998/b184dd71-1812-4c3d-a03c-7a6baecac77f)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
