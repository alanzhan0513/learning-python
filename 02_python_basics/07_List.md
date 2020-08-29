# Python Collections (Arrays)

* List is a collection which is ordered and changeable. Allows duplicate members.
* Tuple is a collection which is ordered and unchangeable. Allows duplicate members.
* Set is a collection which is unordered and unindexed. No duplicate members.
* Dictionary is a collection which is unordered, changeable and indexed. No duplicate members.

# List
``` python
list = ["a", "b", "c"]
print(list)
```

# Access Items
``` python
list = ["a", "b", "c"]
print(list[1])
```

# Negative Indexing
``` python
list = ["a", "b", "c"]
print(list[-1])
```

# Range Of Indexes
``` python
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[2:5])
print(thislist[:4])
print(thislist[-4:-1])
```

# Change Item Value
``` python
thislist = ["apple", "banana", "cherry"]
thislist[1] = "blackcurrant"
print(thislist)
```

# Loop Through a List
``` python
thislist = ["apple", "banana", "cherry"]
for x in thislist:
  print(x)
```

# Check if Item Exists
``` python
thislist = ["apple", "banana", "cherry"]
if "apple" in thislist:
  print("Yes, 'apple' is in the fruits list")
```

# List Length
``` python
thislist = ["apple", "banana", "cherry"]
print(len(thislist))
```

# Add Items
``` python
thislist = ["apple", "banana", "cherry"]
thislist.append("orange")
print(thislist)
```

# Remove Item
## remove()
``` python
thislist = ["apple", "banana", "cherry"]
thislist.remove("banana")
print(thislist)
```

##  pop()
``` python
thislist = ["apple", "banana", "cherry"]
thislist.pop()
print(thislist)
```

## del
``` python
thislist = ["apple", "banana", "cherry"]
del thislist[0]
print(thislist)
```
This will cause an error because you have succsesfully deleted "thislist".
``` python
thislist = ["apple", "banana", "cherry"]
del thislist
print(thislist)
```

# Copy a List
``` python
thislist = ["apple", "banana", "cherry"]
mylist = thislist.copy()
print(mylist)
```

# Join Two Lists
## Plus Operator
``` python
list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

list3 = list1 + list2
print(list3)
```

## append()
``` python
list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

for x in list2:
  list1.append(x)

print(list1)
```

# extend()
``` python
list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

list1.extend(list2)
print(list1)
```

# The list() Constructor
``` python
thislist = list(("apple", "banana", "cherry"))
print(thislist)
```

# List Methods
|Method|Description|
|-|-|
|append()|Adds an element at the end of the list|
|clear()|Removes all the elements from the list|
|copy()|Returns a copy of the list|
|count()|Returns the number of elements with the specified value|
|extend()|Add the elements of a list (or any iterable), to the end of ||the current list|
|index()|Returns the index of the first element with the specified |value
|insert()|Adds an element at the specified position|
|pop()|Removes the element at the specified position|
|remove()|Removes the item with the specified value|
|reverse()|Reverses the order of the list|
|sort()|Sorts the list|
