## Python Practice Task- List Manager

## Solution

~~~
lis=[10,5,20,15,8]
print("Original list:",lis)
print("Sum:", sum(lis))
print("Max:", max(lis))
print("Min:", min(lis))
lis.sort()
print("Sorted:", lis)
lis.reverse()
print("Reversed:",lis)


new_lis=[10,5,20,15,8]
num1=int(input("\nEnter a number to append:"))
new_lis.append(num1)
print("After appending:",new_lis)

num2=int(input("\nEnter a number to insert at index 2:"))
new_lis.insert(2,num2)
print("After inserting:",new_lis)

num3=int(input("\nEnter a number to remove:"))
new_lis.remove(num3)
print("After removing:",new_lis)

new_lis.pop()
print("\nAfter popping the last element:",new_lis)

num4=int(input("\nEnter a number to search:"))
print("Is", num4, "in the list?", num4 in new_lis)
~~~
