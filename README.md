# calculator
A simple calculator application that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. Designed with clean logic for user-friendly interaction, ensuring accurate results. Ideal for practicing fundamental programming concepts and operators.
print("Simple Calculator")
print("operator:+,-,*,/")
while True:
    num1=float(input("enter number1"))
    operator=input("enter operator")
    num2=float(input("enter number2"))
    if operator=="+":
        print("result:addition:",num1+num2)
    elif operator=="-":
        print("result:substraction",num1-num2)
    elif operator=="*":
        print("result:multiplication",num1*num2)
    elif operator=="/":
        if num2!=0:
            print("result:division",num1/num2)
        else:
            print("not allowed")
    else:
        print("Invalid operation")
    break

