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
Program to find the square root for the given number(newton's method) using function.
Developed by:NITHIYANANDAN N
RegisterNumber:212222230099
*/
def newton_sqrt(num,num_iter=100):
    a=float(num)
    for i in range(num_iter):
        num=0.5*(num + a/num)
    return num
number = int(input())
sqrt_value = newton_sqrt(number)
print(f"Square root of the number: {sqrt_value}")
        
```

## Output:
![image](https://github.com/NITHIYANANDAN278/Square-root-of-a-number/assets/121784636/c6241c4f-77ee-4544-ba17-a049fe9af547)





## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
