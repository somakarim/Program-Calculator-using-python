# Program-Calculator-using-python
num=input('Enter first number ')
num1=input('Enter second number ')
choice=input('Enter operator ')
if choice=='+':
    result=int(num)+int(num1)
    print('Addition: ',result)
elif choice=='-':
    result=int(num)-int(num1)
    print('Sub: ',result)
elif choice=='*':
    result=int(num)*int(num1)
    print('Multiplication: ',result)
elif choice=='/':
    result=int(num)/int(num1)
    print('Division: ',result)
else:
    print('Invalid')
