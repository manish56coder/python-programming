# python-programming
#My programs
#My Name is Manish Kushwah
num1= int(input("Enter first Number:"))
num2=int(input("Enter Second Number:"))
operator=input("Choose Your Operator '*' '-' '/' '+':- ")


if num1==45 and num2==9 and operator=='+':
    print("77")
elif num1==56 and num2==5 and operator=='/':
    print("4")
elif operator== '*':   
    multi= num1*num2
    print(multi)
    
elif operator=='-':
    minus= num1-num2
    print(minus)
elif operator=='/':
    divid= num1/num2
    print(divid)
elif operator=='+':
    plus=num1+num2
    print(plus)
else:
    print("Unexpected Error Please Enter Valid command")
    
