# faulty-calculater
#calculater with some faulty result
a = float(input("enter the first number\n"))
b = float(input("enter the second number\n"))
c = input("enter the opreater\n")
if a==45 and b==3 and c=="*" :
    print("555")
elif c=="*":
    print(a*b)
elif a==56 and b==9 and c=="+":
    print("77")
elif c=="+":
    print(a+b)
elif a==56 and b==6 and c=="/":
    print("4")
elif c=="/":
    print(a/b)
elif c=="-":
    print(a-b)
else:
    print("unexpected")
