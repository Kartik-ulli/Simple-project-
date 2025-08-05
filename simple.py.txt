
while True:
    print("simple calculator")
    print("1. addition")
    print("2. substraction")
    print("3. maltiplication")
    print("4. division")
    print("5. Exist")
    a = int(input())
    if a==1:
        b = int(input("enter first number: \n"))
        c = int(input("enter second number: \n"))
        print("result: ", b+c)
    if a==2:
        b = int(input("enter first number: \n"))
        c = int(input("enter second number: \n"))
        print("result: ", b-c)    
    if a==3:
        b = int(input("enter first number: \n"))
        c = int(input("enter second number: \n"))
        print("result: ", b*c)
    if a==4:
        b = int(input("enter first number: \n"))
        c = int(input("enter second number: \n"))
        print("result: ", b/c)
    if a==5:
        print("okay bye from simple calculator \n when you need i am here \n \n")
        break