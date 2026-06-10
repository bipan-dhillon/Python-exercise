## Python Tuple Task- Loop,Join & Multiply

## Solution -

~~~
animals=("cat","dog","rabbit")
colors=("red","blue")

print("Animals using for loop:")
for x in animals:
  print(x)

print("\nColors using while loop:")
i=0
while i<len(colors):
  print(colors[i])
  i=i+1

new=animals+colors
print("\nJoined tuple:",new)

print("Animals repeated 2 times:", animals*2)
print("Colors repeated 3 times:", colors*3)
~~~
