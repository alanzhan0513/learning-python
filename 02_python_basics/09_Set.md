# Set
A set is a collection which is unordered and unindexed. In Python, sets are written with curly brackets.

``` python
thisset = {"apple", "banana", "cherry"}
print(thisset)
```

# Access Items
``` python
thisset = {"apple", "banana", "cherry"}

for x in thisset:
  print(x)
```

Check if "banana" is present in the set:
``` python
thisset = {"apple", "banana", "cherry"}

print("banana" in thisset)
```

# Add Items
``` python
thisset = {"apple", "banana", "cherry"}

thisset.add("orange")

print(thisset)
```

Add multiple items to a set, using the update() method:
``` python
thisset = {"apple", "banana", "cherry"}

thisset.update(["orange", "mango", "grapes"])

print(thisset)
```

# Get the Length of a Set

``` python
thisset = {"apple", "banana", "cherry"}

print(len(thisset))
```

# Remove Item

``` python
thisset = {"apple", "banana", "cherry"}

thisset.remove("banana")

print(thisset)
```

Remove "banana" by using the discard() method:
``` python
thisset = {"apple", "banana", "cherry"}

thisset.discard("banana")

print(thisset)
```

Remove the last item by using the pop() method:

``` python
thisset = {"apple", "banana", "cherry"}

x = thisset.pop()

print(x)

print(thisset)
```

The clear() method empties the set:
``` python
thisset = {"apple", "banana", "cherry"}

thisset.clear()

print(thisset)
```

The del keyword will delete the set completely:
``` python
thisset = {"apple", "banana", "cherry"}

del thisset

print(thisset)
```

# Join Two Sets
The union() method returns a new set with all items from both sets:
``` python
set1 = {"a", "b" , "c"}
set2 = {1, 2, 3}

set3 = set1.union(set2)
print(set3)
```

The update() method inserts the items in set2 into set1:
``` python
set1 = {"a", "b" , "c"}
set2 = {1, 2, 3}

set1.update(set2)
print(set1)
```

# Set Methods
Python has a set of built-in methods that you can use on sets.

|Method|Description|
|-|-|
|add()|Adds an element to the set|
|clear()|Removes all the elements from the set|
|copy()|Returns a copy of the set|
|difference()|Returns a set containing the difference between two or more sets|
|difference_update()|Removes the items in this set that are also included in another, specified set|
|discard()|Remove the specified item|
|intersection()|Returns a set, that is the intersection of two other sets|
|intersection_update()|Removes the items in this set that are not present in other, specified set(s)|
|isdisjoint()|Returns whether two sets have a intersection or not|
|issubset()|Returns whether another set contains this set or not|
|issuperset()|Returns whether this set contains another set or not|
|pop()|Removes an element from the set|
|remove()|Removes the specified element|
|symmetric_difference()|Returns a set with the symmetric differences of two sets|
|symmetric_difference_update()|inserts the symmetric differences from this set and another|
|union()|Return a set containing the union of sets|
|update()|Update the set with the union of this set and others|
