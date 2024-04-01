# calculatorprogram
x = int(input("Enter first number : "))
y = int(input("Enter second number : "))
choice = input("Enter your choice ('+','-','*','/','//','**')");
if choice == '+':
    print("Addition " ,x+y )
elif choice == '-':
    print("substraction" ,x-y)
elif choice == '*':
    print("Multiplication", x*y)
elif choice == '/':
    print("Division" ,x/y)
elif choice == '//':
    print("Floor Division ", x//y)
elif choice == '%':
    print("Module" , x%y)
elif choice == '**':
    print("Exponention ", x**y)
else:
    print("Invalid input")
