# python.py
# Basic Python Program

# Taking input from user
name = input("Enter your name: ")
age = int(input("Enter your age: "))

# Displaying output
print("\nHello,", name + "!")
print("You are", age, "years old.")

# Basic arithmetic
num1 = float(input("\nEnter first number: "))
num2 = float(input("Enter second number: "))

sum_result = num1 + num2
sub_result = num1 - num2
mul_result = num1 * num2
div_result = num1 / num2

print("\nResults:")
print("Addition:", sum_result)
print("Subtraction:", sub_result)
print("Multiplication:", mul_result)
print("Division:", div_result)

# Conditional statement
if age >= 18:
    print("\nYou are an adult.")
else:
    print("\nYou are a minor.")

print("\n--- End of Program ---")
