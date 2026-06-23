## Python Practice Task

## Student Grade Calculator

## Solution-

~~~
def calculate_grade(marks):

    if marks>=90 and marks<=100:
      return "Grade: A"
    elif marks>=75 and marks<=89:
      return "Grade: B"
    elif marks>=50 and marks<=74:
      return "Grade: C"
    elif marks<50:
      return "Grade: D"


def main():
  name=input("Enter student's name:")
  marks1=int(input("Enter student's marks:"))
  calculate_grade(marks1)

  print("\nStudent:",name,"\nMarks:",marks1,"\nGrade:",calculate_grade(marks1))


main()
~~~

## Output-

~~~
Enter student's name:Alice
Enter student's marks:82

Student: Alice 
Marks: 82 
Grade: Grade: B
~~~

