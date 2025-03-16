# assignment-1
x =float(input("enter the first number: "))
y = float (input("enter the second number: "))
operator = input("enter the operator(+, -, *, /,): ")
result: float  =0

if operator == '+':
    result = x + y
elif operator == '-':
    result = x - y
elif operator == '*':
    result = x * y
elif operator == '/':
    if x !=0:
     result = x / y
    else :print("zero can not be divided by a number or you cannot divide a number by zero")

else: print("invalid operator")

print("result", result)
