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
/*
# Program to find the square root for the given number(newton's method) using function.
# Developed by: GOKUL C
# RegisterNumber : 212223240040

def newton_method(number,iterations=100):
    for i in range(iterations):
        number=0.5*(number+inp/number)
    return number
inp=int(input())
print("Square root of the number:",newton_method(inp))
 
*/
```

## Output:
![Screenshot 2024-04-16 165758](https://github.com/Gokul1410/Square-root-of-a-number/assets/153058321/a7af699e-fb1b-4aff-ad7e-e0726b4b000d)
![Screenshot 2024-04-16 165809](https://github.com/Gokul1410/Square-root-of-a-number/assets/153058321/b54966e9-2934-4253-a8f0-1a8452e0754a)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
