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
#To find the gcd of a number using function
#Developed by:Vikaash P
#Register no:212223240180

def gcd():
    number1,number2=int(input()),int(input())
    if number1<number2:
         smaller=number1
    else:
        smaller=number2
    for i in range(1,smaller+1):
        if number1%i==0 and number2%i==0:
            gcd1=i
    print(f"GCD of two numbers is: {gcd1}")
```
                    
## Output:
![image](https://github.com/Vikaash16/GCD-of-two-numbers/assets/139218414/4b8f73b7-17d7-49be-a0ed-37cbc90cd3bc)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
