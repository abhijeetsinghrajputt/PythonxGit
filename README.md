# PythonxGit
def divide(x, y):
    if y != 0:
        return x / y
    else:
        return "Cannot divide by zero"

num1 = float(input("Enter the numerator: "))
num2 = float(input("Enter the denominator: "))

result = divide(num1, num2)
print("The result of the division is:", result)

