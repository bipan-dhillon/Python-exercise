## Task- Advanced Python Assignment : Student Information & Performance Analyzer

## Solution
STEP 1
~~~
name=input("Enter full name:")
age=int(input("Enter age:"))
course=input("Enter course name:")
mark1=eval(input("Enter Python marks:"))
mark2=eval(input("Enter AI marks:"))
mark3=eval(input("Enter Web Developement marks:"))
~~~
STEP 2
~~~
name.upper()
name.lower()
name[0:5]
name[-3:]
len(name)
~~~
STEP 3
~~~
marks_obtained= mark1+mark2+mark3
print("Total Marks:", marks_obtained)
percent= marks_obtained/300
percentage= percent*100
print("Percentage:", percentage,"%")

avg= marks_obtained/3
print("\nAverage Marks:", avg)
~~~
STEP 4
~~~
is_greater_than_80= percentage>=80
print(is_greater_than_80)
is_greater_than_50= percentage>=50
print(is_greater_than_50)
~~~
STEP 5
~~~
print("Scholarship eligibility check:")
print("\neligible:", percentage>=80 and age<=25)
~~~
STEP 6
~~~
sub=["Python","AI","Web Development"]
sub_name=input("Enter a subject name:")
print("Subject present:",sub_name in sub)
~~~
STEP 7
~~~
a="---------------------------------------------------"
print(a.center(50))
x="STUDENT REPORT"
print(x.center(50))
print(a.center(50))

print("Name".center(10), ":".center(20) ,name)
print("Course".center(10),":".center(20), course)
print("Age".center(10),":".center(20), age)

print("\nTotal Marks".center(10),":".center(20), marks_obtained)
print("Percentage".center(10),":".center(20), percentage,"%")
print("Average Marks".center(10),":".center(20), avg)

print("Excellent".center(10),":".center(20), percentage>=80)
print("Passed".center(10),":".center(20), percentage>=50)
print("Scholarship".center(10),":".center(20), percentage>=80 and age<=25)

print("\nSubject Found".center(10),":".center(20), sub_name in sub)
print(a.center(50))
~~~
