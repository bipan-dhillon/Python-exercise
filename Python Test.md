## Python Test 

## PART B- PRACTICAL

## Solution-

## Task 1
~~~
student_name=input("Enter student's name:")
roll_no=int(input("Enter student's roll no.:"))
age=int(input("Enter student's age:"))
course=input("Enter student's course:")
~~~

## OUTPUT
~~~
Enter student's name:Rahul
Enter student's roll no.:101
Enter student's age:20
Enter student's course:B.Tech
~~~

---

## Task 2
~~~
print("Name Data Type:", type(student_name))
print("Roll No. Data Type:", type(roll_no))
print("Age Data Type:", type(age))
print("Course Data Type:", type(course))
~~~

## OUTPUT
~~~
Name Data Type: <class 'str'>
Roll No. Data Type: <class 'int'>
Age Data Type: <class 'int'>
Course Data Type: <class 'str'>
~~~

---

## Task 3
~~~
mark1=int(input("Enter marks of first subject:"))
mark2=int(input("Enter marks of second subject:"))
mark3=int(input("Enter marks of third subject:"))

marks=[mark1, mark2, mark3]
print("\nmarks=",marks)

print("\nMarks of all subjects:")
print("First Subject:",marks[0])
print("Second Subject:",marks[1])
print("Third Subject:",marks[2])

print("\nHighest Marks:", mark3)
print("Lowest Marks:", mark1)


total_marks=mark1+mark2+mark3
print("\nTotal Marks:", total_marks)
~~~

## OUTPUT
~~~
Enter marks of first subject:78
Enter marks of second subject:85
Enter marks of third subject:90

marks= [78, 85, 90]

Marks of all subjects:
First Subject: 78
Second Subject: 85
Third Subject: 90

Highest Marks: 90
Lowest Marks: 78

Total Marks: 253
~~~

---

## Task 4
~~~
subjects=("Python","Web Developement","Database")

print("All Subjects:", "\n",subjects[0],"\n",subjects[1],"\n",subjects[2])
print("\nFirst Subject:", subjects[0])
print("Last Subject:", subjects[-1])

subj_lis=list(subjects)
print("Total Subjects Count:",len(subj_lis))
subjects=tuple(subj_lis)
~~~

## OUTPUT
~~~
All Subjects: 
 Python 
 Web Developement 
 Database

First Subject: Python
Last Subject: Database
Total Subjects Count: 3
~~~

---

## Task 5
~~~
marks.append(95)
print("After adding:", marks)

marks.remove(78)
print("After removing:",marks)

marks.sort()
print("After sorting:", marks)

print("Updated list:",marks)
~~~

## OUTPUT
~~~
After adding: [78, 85, 90, 95]

After removing: [85, 90, 95]

After sorting: [85, 90, 95]

Updated list: [85, 90, 95]
~~~

---

## Task 6
~~~
print("="*20,"STUDENT REPORT","="*20)

print("\nName:",student_name)
print("\nRoll Number:",roll_no)
print("\nAge:",age)
print("\nCourse:",course)
print("\nSubjects:",subjects)
print("\nMarks:",marks)
print("\nHighest Marks:",mark3)
print("\nLowest Marks:",mark1)
print("\nTotal Marks:",total_marks)

print("="*55)
~~~

## OUTPUT
~~~
==================== STUDENT REPORT ====================

Name: Rahul

Roll Number: 101

Age: 20

Course: B.Tech

Subjects: ('Python', 'Web Developement', 'Database')

Marks: [78, 85, 90]

Highest Marks: 90

Lowest Marks: 78

Total Marks: 253
=======================================================
~~~

---

## Bonus Challenge

## 1.)
~~~
avg= (mark1+mark2+mark3)/len(marks)
print("Average Marks:",avg)
~~~

## OUTPUT
~~~
Average Marks: 84.33333333333333
~~~

## 2.)
~~~
print("PASSED:", avg>=40)
~~~

## OUTPUT
~~~
PASSED: True
~~~
















