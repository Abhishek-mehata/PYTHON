
List Sorting 
---

Sorting is the process of arranging data items in many orders like ascending order , descending order , and many more.

----------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------

Sort List Alphanumerically
---

```
List objects have a 'sort()' method that will sort the list alphanumerically, ascending, by default.

Eg1:
# Sort the list alphabetically
thislist = ["orange", "mango", "kiwi", "pineapple", "banana"]
thislist.sort()
print(thislist)
---------------------------------------------------------

Eg2:
# Sort the list numerically
thislist = [100, 50, 65, 82, 23]
thislist.sort()
print(thislist)

```
----------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------

Sort Descending
---
```
To sort descending, use the keyword argument 'reverse = True' or use 'reverse = False' for ascending order.

Eg1:
# Sort the list descending.
thislist = ["orange", "mango", "kiwi", "pineapple", "banana"]
thislist.sort(reverse = True)
print(thislist)

---------------------------------------------------

Eg2:
# Sort the list descending.
thislist = [100, 50, 65, 82, 23]
thislist.sort(reverse = True)
print(thislist)

---------------------------------------------------

Eg3:
# Sort the list ascending.
thislist = ["orange", "mango", "kiwi", "pineapple", "banana"]
thislist.sort(reverse = False)
print(thislist)

```
-----------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------

Customize Sort Function
---

```
You can also customize your own function by using the keyword argument key = function.

Eg1:
def myfunc(n):
  return abs(n - 50)

thislist = [100, 50, 65, 82, 23]
thislist.sort(key = myfunc)
print(thislist)
```

-----------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------

Case Insensitive Sort
---

```
By default the sort() method is case sensitive, resulting in all capital letters being sorted before lower case letters


Eg:
# Case sensitive sorting can give an unexpected result:
thislist = ["banana", "Orange", "Kiwi", "cherry"]
thislist.sort()
print(thislist)
```
------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------

```
# Luckily we can use built-in functions as key functions when sorting a list.
# So if you want a case-insensitive sort function, use str.lower as a key function.

Eg:
# Perform a case-insensitive sort of the list
thislist = ["banana", "Orange", "Kiwi", "cherry"]
thislist.sort(key = str.lower)
print(thislist)
```

------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------


Reverse Order
---
```
What if you want to reverse the order of a list, regardless of the alphabet?
The reverse() method reverses the current sorting order of the elements.

Eg:
# Reverse the order of the list items:
thislist = ["banana", "Orange", "Kiwi", "cherry"]
thislist.reverse()
print(thislist)
```
------------------------------------------------------------------------------------------------------------------
[**Best of Luck**]