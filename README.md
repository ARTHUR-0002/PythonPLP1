# PythonPLP1

def main():
    # Get user input for the first number
    num1 = float(input("Enter the first number: "))
    
   num2 = float(input("Enter the second number: "))
    
   operation = input("Enter the operation (add, subtract, multiply, divide): ").strip().lower()
    

   if operation == 'add':
        result = num1 + num2
        print(f"The result of {num1} + {num2} is: {result}")
   elif operation == 'subtract':
        result = num1 - num2
        print(f"The result of {num1} - {num2} is: {result}")
   elif operation == 'multiply':
        result = num1 * num2
        print(f"The result of {num1} * {num2} is: {result}")
  elif operation == 'divide':
        if num2 != 0:
            result = num1 / num2
            print(f"The result of {num1} / {num2} is: {result}")
   else:
            print("Error: Division by zero is not allowed.")
  else:
        print("Invalid operation. Please enter add, subtract, multiply, or divide.")

if __name__ == "__main__":
    main()
