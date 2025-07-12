# python5
Functions within Functions

def cal(a,b):
    def add():
        return a+b
    def sub():
        return a-b
    def mul():
        return a*b
    def div():
        return a//b
    print("Addition", add())
    print("Subtract", sub())
    print("Product", mul())
    print("Divide", div())
a= int(input("Enter a number:"))
b= int(input("Enter a number:"))
cal(a,b)
