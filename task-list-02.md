## Python Task- List Methods Practice

## Solution

~~~
num=[10,20,30,40]
alpha=["apple","banana"]
print("Original Numbers:",num)
num.append(50)
print("After append:",num)
num.insert(1,15)
print("After insert:",num)
num.extend(alpha)
print("After extend:", num)
num.remove(40)
print("After remove:", num)
num.pop(2)
print("After pop:", num)

new=[10,15,30,50]
new.sort()
print("Sorted numbers:",new)

num.reverse()
print("Reversed:",num)
num.clear()
print("Cleared:",num)
~~~
