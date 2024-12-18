def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Error! Division by zero."
    else:
        return x / y

# Display the menu
def display_menu():
    print("Select operation:")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    print("4. Divide")

# Main code to drive the calculator
def calculator():
    while True:
        # Show the menu
        display_menu()

        # Take user input for operation
        choice = input("Enter choice (1/2/3/4) or 'q' to quit: ")

        # If the user chooses to quit, exit the loop
        if choice == 'q':
            print("Exiting calculator. Goodbye!")
            break

        # Check if the input is valid
        if choice in ['1', '2', '3', '4']:
            try:
                # Take the numbers for the operation
                num1 = float(input("Enter first number: "))
                num2 = float(input("Enter second number: "))

                # Perform the calculation based on user's choice
                if choice == '1':
                    print(f"The result is: {add(num1, num2)}")
                elif choice == '2':
                    print(f"The result is: {subtract(num1, num2)}")
                elif choice == '3':
                    print(f"The result is: {multiply(num1, num2)}")
                elif choice == '4':
                    print(f"The result is: {divide(num1, num2)}")
            except ValueError:
                print("Invalid input. Please enter numeric values.")
        else:
            print("Invalid choice. Please select a valid operation.")

# Run the calculator
if __name__ == "__main__":
    calculator()
