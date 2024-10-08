Python - Access List Items

---

Access Items
---
```
List items are indexed and you can access them by referring to the index number.
Indexing of first element starts from 0 and so on for other elements.

Eg:
# Print the second item of the list:
thislist = ["apple", "banana", "cherry"]
print(thislist[1])

# indexing of list items starts from 0
```

-----------------------------------------------------------------------------------------------------------------------
-------------

Negative Indexing
---

```
Negative indexing means start from the end.
-1 refers to the last item, -2 refers to the second last item ....

Eg:

# Print the last item of the list:
thislist = ["apple", "banana", "cherry"]
print(thislist[-1])
```
-------------------------------------------------------------------------------------------------------------------
-----------------

List Slicing
---

```
You can specify a range of indexes by specifying where to start and where to end the range.
This will give a range of elements between starting and ending index.

In python List slicing we have to Specify the slicing starting index and the [ending index+1], separated by a colon, to return a part of the List.

---------------------------------------------
Eg1:

# Return the third, fourth, and fifth item[index 2nd to 4th index. Remember 5th index is not included]
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[2:5])
# The search will start at index 2 (included) and end at index 5 (not included).

---------------------------------------------
By leaving out the start value, the range will start at the first item

Eg2:
# This example returns the items from the beginning to, (4-1=3rd) index
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[:4])

---------------------------------------------

By leaving out the end value, the range will go on to the end of the list

Eg3:
# This example returns the items from "cherry" to the end

thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[2:])
```
----------------------------------------------------------------------------------------------------------
------------


List Slicing by negative index
---
```
Specify negative indexes if you want to start the search from the end of the list.

Eg:
# This example returns the items from "orange" (-4) to, (-2) but NOT including "mango" (-1):
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[-4:-1])
```

--------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------

Check if Item Exists
----

```
To determine if a specified item is present in a list use the in keyword.

Eg:

# Check if "apple" is present in the list
thislist = ["apple", "banana", "cherry"]
if "apple" in thislist:
  print("Yes, 'apple' is in the fruits list")
```
<!-- ------------------------------------------------------------------------ -->
[**Best of Luck**]
