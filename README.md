# a-simple-calculator
The code is written: 02/09/26 this is a simple calculator! maybe I'll release an improved version later.
```Python
a = float(input("First number: "))
b = float(input("Second number: "))
operation = input("Choose: /, *, +, - ")

if operation == "/":
    print(f"{a / b}")
    
elif operation == "*":
    print(f"{a * b}")
    
elif operation == "+":
    result = a + b
    print(f"{a + b}")
    
elif operation == "-":
    result = a - b
    print(f"{a - b}")
    
else:
    print("Error")
