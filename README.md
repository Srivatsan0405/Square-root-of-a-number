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
#program to find the square root for the given number(newton's method) using function.
#Developed By:SRIVATSAN V
#Reg No:23000970
def sq_root(a):
    x=0.5*a
    y=0.5*(x+a/x)
    while y!=x:
        x=y
        y=0.5 *(x+a/x)
    return x
n=int(input())
print("Square root of the number:",sq_root(n))

```

## Output:
![Screenshot 2023-12-26 104419](https://github.com/Srivatsan0405/Square-root-of-a-number/assets/139841630/c4f84a29-859e-4d87-8a6c-955207ccc4d0)
![Screenshot 2023-12-26 104223](https://github.com/Srivatsan0405/Square-root-of-a-number/assets/139841630/ffbcd838-6adb-4485-b092-35c0901fdbf3)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
