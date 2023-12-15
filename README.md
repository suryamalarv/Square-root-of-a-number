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
Developed by: suryamalarv
RegisterNumber:  23013656
*/
```
num=int(input())
a=1e-6
max=100

guess=num/2.0
for _ in range(max):
    new=0.5*(guess+num/guess)
    if abs(new-guess)<a:
       break
    guess=new
print(f"Square root of the number: {new}") 
```

## Output:
![Screenshot 2023-12-15 111650](https://github.com/suryamalarv/Square-root-of-a-number/assets/145742486/81aebba0-f24a-4024-a2d3-40e44382b3a6)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
