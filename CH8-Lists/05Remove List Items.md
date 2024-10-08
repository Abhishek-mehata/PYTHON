Remove Specified Item
---

```
The 'remove()' method removes the specified item.

Eg1:
# Remove 'banana'
thislist = ["apple", "banana", "cherry"]
thislist.remove("banana")
print(thislist)

# Note: If there are more than one item with the same value, the remove() method removes the first occurrence.
-----------------------------------------------------------------------------
Eg2:
# Remove the first occurrence of "banana":
thislist = ["apple", "banana", "cherry", "banana", "kiwi"]
thislist.remove("banana")
print(thislist)
```

------------------------------------------------------------------------------------------------------
------------------

Remove Specified Index
---

```
The 'pop()' method removes the specified index element.

Eg1:
# Remove the second item
thislist = ["apple", "banana", "cherry"]
thislist.pop(1)
print(thislist)

# Note:If you do not specify the index, the pop() method removes the last item.

-----------------------------------------------------------------------------------
Eg2:
# Remove the last item
thislist = ["apple", "banana", "cherry"]
thislist.pop()
print(thislist)

```
----------------------------------------------------------------------------------------------------------
--------------

'del'
---

```
# The 'del' keyword also removes the specified index.

Eg1:
# Remove the first item
thislist = ["apple", "banana", "cherry"]
del thislist[0]
print(thislist)

----------------------------------------------------------------
# The 'del' keyword can also delete the list completely.

Eg2:
# Delete the entire list
thislist = ["apple", "banana", "cherry"]
del thislist
```

----------------------------------------------------------------------------------------------
----------------------------------------

Clear the List
---
```
The 'clear()' method empties the list.
The list still remains, but it has no content.

Eg:
# Clear the list content
thislist = ["apple", "banana", "cherry"]
thislist.clear()
print(thislist)
```

---
[**Best of Luck**]