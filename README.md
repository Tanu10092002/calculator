# calculator
git clone https://github.com/Tanu10092002/calculator.git
cd calculator

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y != 0:
        return x / y
    else:
        return "Error: Cannot divide by zero"

if __name__ == "__main__":
    print("Calculator Program")
git add calculator.py
git commit -m "Initial commit: Added calculator program"


