# printing-factorial-of-given-number-using-function
def fact(n):
    if(n<0):
        print("factorial is undefined")
    elif(n==0):
        print("factorial is 1")
    else:
        factorial=1
        for i in range(1,n+1):
            factorial=factorial*i
        return factorial
n=int(input("enter any positive integer:"))
print("the factorial of ",n,"is",fact(n))
