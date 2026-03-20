# simple-calculator

a = float(input("enter the value of a: "))
b = float(input("enter the value of b: "))

op = input("enter operator (+,-,*,/): ")

if op == "+":
    print("result:", a+b)
elif op == "-":
    print("result:", a-b)
elif op == "*":
    print("result:", a*b)
elif op == "/":
    if a != 0:
        print("result:", a/b)
    else:
        print("invalid")

else:
   print("invalid operator")


    
This is my first project. In this i made a simple calculator with the help of python
