# calculatorprogram<br>
x = int(input("Enter first number : "))<br>
y = int(input("Enter second number : "))<br>
choice = input("Enter your choice ('+','-','*','/','//','**')");<br>
if choice == '+':<br>
    print("Addition " ,x+y )<br>
elif choice == '-':<br>
    print("substraction" ,x-y)<br>
elif choice == '*':<br>
    print("Multiplication", x*y)<br>
elif choice == '/':<br>
    print("Division" ,x/y)<br>
elif choice == '//':<br>
    print("Floor Division ", x//y)<br>
elif choice == '%':<br>
    print("Module" , x%y)<br>
elif choice == '**':<br>
    print("Exponention ", x**y)<br>
else:<br>
    print("Invalid input")<br>
