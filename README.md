# First_project

print("<========>Calculator<========>")

NUM1 = int(input("Enter first number : "))
NUM2 = int(input("Enter second number : "))

operator = input("Enter the operator to be perfored : ")

match(operator):
    case "+":
        print(f"Result : {NUM1 + NUM2}")
    case "-":
        print(f"Result : {NUM1 + NUM2}")
    case "/":
        print(f"Result : {NUM1 + NUM2}")
    case "*":
        print(f"Result : {NUM1 + NUM2}")
    case _:
        print(f"Invalid or Complited.")
