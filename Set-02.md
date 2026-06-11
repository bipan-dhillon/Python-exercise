## Python Set Assignment- Student Club Management System

## Solution-

~~~
science_club={"Aman","Riya","Karan","Simran"}
sports_club={"Karan","Simran","Rahul","Neha"}

new_sci=input("Enter a new Science Club member:")
science_club.add(new_sci)
print("\nScience Club:")
print(science_club)

rem_spor=input("\nEnter a sports club member to remove:")
print("\nSports Club:")
sports_club.remove(rem_spor)
print(sports_club)

print("\nCommon Members:")
comman=science_club.intersection(sports_club)
print(comman)

all_mem=science_club|sports_club
print("\nAll Members:")
print(all_mem)

sci_only=science_club.difference(sports_club)
print("\nScience Club Only:")
print(sci_only)

to_find=input("Enter a student name to search:")
print(to_find,"is a member of science club.",to_find in science_club)

temp_set={"Test1","Test2","Test3"}
print("\nTemporary set before clear:")
print(temp_set)
print("\nTemporary set after clear:")
temp_set.clear()
print(temp_set)
~~~
