# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
Write a Python program to check whether the given number is Even number and it is greater than or equal to 25 or not using nested if..else.

For example:

Input	Result
26
26 is an Even number
26 is greater than or equal to 25
5
5 is NOT an Even number


## Output
num=int(input())
if(num % 2 == 0):
    print(f"{num} is an Even number")
    if num >= 25:
        print(f"{num} is greater than or equal to 25") 
    else:
        print(f"{num} is lesser than 25")
else:
    print(f"{num} is NOT an Even number")
    

## Result
Thus the odd and even numbers are verified through conditional statements in python.

