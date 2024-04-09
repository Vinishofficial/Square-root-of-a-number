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
#Square-root-of-a-number
#Developed by: VINISHRAJ R
#RegisterNumber:  212223230243

def sqroot(num,iter=100):
    a=float(num)
    for i in range(iter):
        num=0.5*(num+a/num)
    return num
a=int(input())
print("Square root of the number:",sqroot(a))

*/
```

## Output:
![Screenshot 2024-03-23 085100](https://github.com/Vinishofficial/Square-root-of-a-number/assets/146931793/b0b9f904-57a8-441f-a264-9515e0c04f01)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
