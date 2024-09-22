# DATE:
# EX-4: Find the GCD of two numbers

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
#Developed by: Harsshitha lakshmanan
#Register no: 212223230075
def gcd():
    n1=int(input())
    n2=int(input())
    if n1>n2:
        smaller=n2
    else:
        samller=n1
    for i in range(1,smaller+1):
        if n1%i==0 and n2%i==0:
            gcd1=i
    print(f"GCD of two numbers is: {gcd1}")
```

## Output:
![image](https://github.com/user-attachments/assets/c3a0cf92-517e-4ad6-8eaf-ab4ec826f6b4)
![image](https://github.com/user-attachments/assets/0f8a3ab3-71ab-4ff8-81e9-3f5f1c0fc335)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
