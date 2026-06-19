## Python Practice Task

## Solution-

~~~
def add(x,y):
  return (x+y)

def diff(x,y):
  return (x-y)

def prod(x,y):
  return (x*y)

def divi(x,y):
  if y==0:
    print("Can't divide by zero")
  else:
    return (x/y)


def main():
  x=eval(input("Enter first number:"))
  y=eval(input("Enter second number:"))
  ope=input("Choose operation (+,-,*,/):")

  if ope=="+":
    print("\nResult:",x,ope,y,"=",add(x,y))
  elif ope=="-":
    print("\nResult:",x,ope,y,"=",diff(x,y))
  elif ope=="*":
    print("\nResult:",x,ope,y,"=",prod(x,y))
  elif ope=="/":
    print("\nResult:",x,ope,y,"=",divi(x,y))

main()
~~~
