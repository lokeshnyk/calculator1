# calculator1

#Function to add two numbers
def add(num1, num2):
    return num1 + num2

#Function to subtract two numbers
def subtract (num1, num2) :
    return num1 - num2

#Function tomultiply two numbers
def multiply (num1, num2) :
    return num1 * num2

#Function to divide two numbers
def divide (num1, num2) :
    return num1 / num2


# Take input from the user
select = int(input("select operation form 1, 2, 3, 4 :" ))


number_1 = int(input("Enter first number: "))
number_2 = int(input("Enter second number: "))


if select == 1:
    print(number_1, "+" , number_2, "=" ,
          add(number_1, number_2))

elif select == 2:
     print(number_1, "-" , number_2, "=" ,
          subtract(number_1, number_2))

elif select == 3:
     print(number_1, "*" , number_2, "=" ,
          multiply(number_1, number_2))

elif select == 4:
     print(number_1, "/" , number_2, "=" ,
          divide(number_1, number_2))

else:
    print("invalid input")
