# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```

Program to find the gcd of two number using function.
Developed by:Gowrisankar.p 
RegisterNumber:212222230041  
def gcd():
    x=int(input())
    y=int(input())
    if x<y:
        small=x
    else:
        small=y
    for i in range(1,small+1):
        if(x%i==0 and y%i==0):
            gcd=i
    print("GCD of two numbers is:",gcd)                   
```

## Output:
![image](https://github.com/gowrisankarponnusamy/GCD-of-two-numbers/assets/119393123/d621c745-9482-4f21-b79d-16fdfaa8a6ce)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
