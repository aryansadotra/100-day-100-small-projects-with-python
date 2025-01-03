# 100-day-100-small-projects-with-python

1. Basic Calculator
---------------------   
   
a. simple non defined of two numbers
--------------------------------------
a = 12.5<br><br>
b = 2346<br><br>
print(float(a)+float(b))<br><br>
print(float(a)-float(b))<br><br>
print(float(a)*float(b))<br><br>
print(float(a)%float(b))<br><br>
print(float(a)/float(b))<br><br>
print(float(a)//float(b))<br><br>

b. user defined calculator of two numbers
-------------------------------------------
a = float(input("enter the value of a : "))<br><br>
b = float(input("enter the value of b : "))<br><br>
print(float(a)+float(b))<br><br>
print(float(a)-float(b))<br><br>
print(float(a)*float(b))<br><br>
print(float(a)%float(b))<br><br>
print(float(a)/float(b))<br><br>
print(float(a)//float(b))<br><br>

c. if else calculater
-----------------------
print("Choose operator")

print("1. Addition (+)")<br><br>
print("2. Subtraction (-)")<br><br>
print("3. Division (/)")<br><br>
print("4. Modulo (%)")<br><br>
print("5. Multiplication (*)")<br><br>

try:<br><br>
    operator = int(input("Enter the number corresponding to the operator (1-5): "))<br><br>
    a = float(input("Enter the value of a: "))<br><br>
    b = float(input("Enter the value of b: "))<br><br>

    if operator == 1:<br><br>
        print(f"The result of {a} + {b} is: {a + b}")<br><br>
    
    elif operator == 2:<br><br>
        print(f"The result of {a} - {b} is: {a - b}")<br><br>
    
    elif operator == 3:<br><br>
        if b != 0:<br><br>
            print(f"The result of {a} / {b} is: {a / b}")<br><br>
        else:<br><br>
            print("Error: Division by zero is not allowed.")<br><br>
    
    elif operator == 4:<br><br>
        print(f"The result of {a} % {b} is: {a % b}")<br><br>
    
    elif operator == 5:<br><br>
        print(f"The result of {a} * {b} is: {a * b}")<br><br>
    
    else:<br><br>
        print("Invalid operation selected.")<br><br>

except ValueError:<br><br>
    print("Invalid input. Please enter numeric values.")<br><br>

**2. Program should use time module to get the current hour**
--------------------------------------------------------------
import time
timestamp = time.strftime('%H:%M:%S')
print(timestamp)
timestamp = time.strftime('%H')
print(timestamp)
timestamp = time.strftime('%M')
print(timestamp)
timestamp = time.strftime('%S')
print(timestamp)
# https://docs.python.org/3/library/time.html#time.strftime
