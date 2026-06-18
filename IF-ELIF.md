## Python Tasks

## Solution-

## Task 1
~~~
num=eval(input("Enter a number:"))

if num>0:
  print("Number is positive.")
elif num<0:
  print("Number is negative.")
else:
  print("Number is zero.")
~~~

## Task 2

~~~
mark=eval(input("Enter your marks:"))
if mark>=90 and mark<=100:
  print("Your grade is: A")
elif mark>=80 and mark<=89:
  print("Your grade is: B")
elif mark>=70 and mark<=79:
  print("Your grade is: C")
elif mark>=60 and mark<=69:
  print("Your grade is: D")
elif mark<60:
  print("Failed")
~~~

## Task 3

~~~
no1=eval(input("Enter first number:"))
no2=eval(input("Enter second number:"))
no3=eval(input("Enter third number:"))

num_list=[no1,no2,no3]


if no1>no2 and no1>no3:
  print("\nFirst number is largest.")
elif no3>no1 and no3>2:
    print("\nThird number is largest.")
else:
    print("\nSecond number is largest.")
~~~

## Task 4

~~~
user_name=input("Enter your username:")
password=int(input("Enter your password:"))

if user_name!="admin":
  print("Invalid User")
elif password!=1234:
  print("Invalid Password")
else:
  print("\nLogin Successful")
~~~

## Task 5

~~~
units=int(input("Enter usage units:"))

if units<100:
  print("Low Usage")
elif units>=100 and units<=300:
  print("Medium Usaage")
elif units>300:
  print("High Usage")
~~~

## Task 6

~~~
age=eval(input("Enter your age:"))

if age>=0 and age<=12:
  print("Child")
elif age>=13 and age<=19:
  print("Teenager")
elif age>=20 and age<=59:
  print("Adult")
elif age>=60:
  print("Senior Citizen") 
~~~

## Task 7

~~~
acc_balance=10000
withdrawal=int(input("Enter withdrawal amount:"))

if withdrawal<acc_balance:
  print("\nWithdrawal Successful")
elif withdrawal==acc_balance:
  print("\nAccount Empty")
else:
  print("\nInsufficient Balance")
~~~

## Task 8

~~~
no1=eval(input("Enter first number:"))
no2=eval(input("Enter second number:"))
ope=input("Enter operator:")

if ope=="+":
  print("\nResult:",no1+no2)
elif ope=="-":
  print("\nResult:",no1-no2)
elif ope=="*":
  print("\nResult:",no1*no2)
elif ope=="/":
  print("\nResult:",no1/no2)
~~~

