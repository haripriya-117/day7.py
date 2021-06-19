# day7.py
day7.py
#function grtting two integer inputs from user&print the following:
a=int(input("enter the first value:"))
b=int(input("enter the secon value:"))
op=input("enter '+'for add ,'-'sub,'*' for mul,'/'for div")
def math_function(a,b,op):
    if op=='+':
        print("add of a and b is ",str(a+b))
    elif op=='-':
        print("sub of a and b is",str(a-b))
    elif op=='*':
        print("mul of a and b is ",str(a*b))
    elif op=='/':
        print("division of a a and b ",str(a/b))
math_function(a,b,op)

#function covid()&it accept patient name ,body temperature

def covid(name,temp):
    print("name of patients",name)
    if temp=='':
        print("body temperature:98")
    else:
        print("body temperature:",temp)

name=input("enter the patient name:")
temp=input("enter body temperature")
covid(name,temp)
