# Tuple
``` python
a = ("a", "b", "c")
print(a)
```

# Access Tuple Items
``` python
thistuple = ("apple", "banana", "cherry")
print(thistuple[1])
```

# Negative Indexing
``` python
thistuple = ("apple", "banana", "cherry")
print(thistuple[-1])
```

# Loop Through a Tuple
``` python
thistuple = ("apple", "banana", "cherry")
for x in thistuple:
  print(x)
```

# Check if Item Exists
``` python
thistuple = ("apple", "banana", "cherry")
if "apple" in thistuple:
  print("Yes, 'apple' is in the fruits tuple")
```

# Length
``` python
thistuple = ("apple", "banana", "cherry")
print(len(thistuple))
```

# Add Items
Add Items
Once a tuple is created, you cannot add items to it. Tuples are `unchangeable`.
``` python
thistuple = ("apple", "banana", "cherry")
thistuple[3] = "orange" # This will raise an error
print(thistuple)
```

# Create Tuple With One Item
```  python
thistuple = ("apple",)
print(type(thistuple))

#NOT a tuple
thistuple = ("apple")
print(type(thistuple))
```

# Remove Items
Tuples are unchangeable, so you cannot remove items from it, but you can delete the tuple completely
``` python
thistuple = ("apple", "banana", "cherry")
del thistuple
print(thistuple) #this will raise an error because the tuple no longer exists
```

# Join Two Tuples
``` python
tuple1 = ("a", "b" , "c")
tuple2 = (1, 2, 3)

tuple3 = tuple1 + tuple2
print(tuple3)
```

# Tuple Methods
Python has two built-in methods that you can use on tuples.

|Method|Description|
|-|-|
|count()|Returns the number of times a specified value occurs in a tuple|
|index()|Searches the tuple for a specified value and returns the position of where it was found|