a=print("Enter your first number")
a=int(input())
b=print("Enter your second number")
b=int(input())
x=print("Enter the operator", '+','-','*','/')
x=input()
#check for faulty case
if a == 45 and b == 3 and x=='*':
    print("555")
elif a==56 and b==9 and x=='+':
        print("77")
elif a==56 and b==6 and x=='/':
            print("4")
    #check for actual calculation
elif x =='+':
         c = a + b
         print(c)
elif x=='-':
    c = a - b
    print(c)
elif x=='*':
        c = a * b
        print(c)
elif x=='/':
            c = a / b
            print(c)
else:
    print("Unknown error")
