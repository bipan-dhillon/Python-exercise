## Python Tuple Practice

## Solution-

## Task1
~~~
fruits=("apple","banana","cherry","apple","mango","banana")
print("First fruit is:",fruits[0])
print("Last fruit is:",fruits[-1])

new_tuple=fruits[0:3]
print("\nNew:",new_tuple)

fruits1=list(new_tuple)
fruits1.append("grape")
fruits1.insert(0,"kiwi")
new_tuple=tuple(fruits1)
print("\nAfter Concatinating:",new_tuple)

fruits2=fruits*2
print("\nRepeated tuple:",fruits2)

lis=list(fruits)
lis.append("orange")
fruits=tuple(lis)
print("\nAdded orange:",fruits)
~~~

## Task2

~~~
student=("Alice",21,"Computer Science","Delhi")

print("Student Name:",student[0])
print("Student City:",student[-1])

stud=list(student)
stud[1]=22
stud.insert(3,"Python")
student=tuple(stud)
print("\nAfter changing:",student)

name,age,subj,course,city= student
print("\nName:",name)
print("Age:",age)
print("Subj:",subj)
print("Course:",course)
print("City:",city)
~~~

## Task3

~~~
numbers=(1,2,3,4,5)
letters=("A","B","C")

print("Using for loop:")
for x in numbers:
  print(x)

print("\nUsing while loop:")
i=0
while i<len(letters):
  print(letters[i])
  i=i+1

new=numbers+letters
print("\nAfter Joining:", new)

print("\nRepeating letters:", letters*3)
print("Repeating numbers:", numbers*2)
~~~

## Task4

~~~
student=("Alice",21,"Computer Science","Delhi")
marks=(85,90,78,92,88)

print("Student Name:", student[0])
print("Student City:", student[-1])
print("First marks:", marks[0])
print("Last marks:", marks[-1])

lis=list(student)
lis[1]=22
lis.insert(3,"Python")
student=tuple(lis)
print("\nAfter Updating:",student)

name,age,subj,course,city= student
print("\nName:",name)
print("Age:",age)
print("Subj:",subj)
print("Course:",course)
print("City:",city)

print("\nUsing for loop:")
for x in marks:
  print(x)

  
print("\nUsing while loop:")
NAME="Alice"
i=0
while i<len(NAME):
  print(NAME[i])
  i=i+1

NEW=student+marks
print("\nAfter Joining:",NEW)

print("\nAfter Repeating:", marks*2)
tup=("Python",)
print("After Repeating:", tup*3)
~~~
