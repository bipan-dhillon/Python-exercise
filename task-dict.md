## Python Practice Task- Student Score Manager

## Solution

~~~
student_score={}

for i in range(3):
  name=input(f"Enter student {i+1} name:")
  score=eval(input(f"Enter {name}'s score:"))
  student_score[name]=score


print("\n")
print("-"*3,"Student Record","-"*3)

print("\nStudent Records:",student_score)
print("All Students:", list(student_score.keys()))
print("All Scores:", list(student_score.values()))

top_student=max(student_score, key= student_score.get)
print(f"Top Scorer:{top_student} with {student_score[top_student]}")
~~~
