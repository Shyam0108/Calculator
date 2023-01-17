def calculator():
    while True:
        print("Enter 'q' to quit.")
        num1 = input("Enter a number: ")
        if num1 == 'q':
            break
        num2 = input("Enter another number: ")
        if num2 == 'q':
            break
        operator = input("Enter an operator (+, -, *, /): ")
        if operator == 'q':
            break

        num1 = float(num1)
        num2 = float(num2)

        if operator == '+':
            print(num1 + num2)
        elif operator == '-':
            print(num1 - num2)
        elif operator == '*':
            print(num1 * num2)
        elif operator == '/':
            print(num1 / num2)
        else:
            print("Invalid operator")

calculator()
