## Python Sets- Task & Solution

## Soltion-

~~~
fruits={"apple","banana","cherry"}
print("Initial fruits set:",fruits)

fruits.add("mango")
print("After adding mango:", fruits)

fruits1={"orange","grapes"}
fruits.update(fruits1)
print("After adding multiple:", fruits)

fruits.remove("banana")
print("After removing banana:", fruits)

fruits.discard("kiwi")
print("After discarding kiwi (no error):", fruits)

tropical={"mango","papaya","pineapple"}
uni=fruits|tropical
print("\nUnion:",uni)

intersec=fruits.intersection(tropical)
print("Intersection:",intersec)

uni.difference_update(tropical)
print("Difference:",uni)

print("\nLength of fruits:", len(fruits))
tropical.clear()
print("Tropical after clear:", tropical)
~~~
