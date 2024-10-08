Removing Items
---

There are several methods to remove items from a dictionary.
---

```
Eg1:
# The 'pop()' method removes the item with the specified key name:

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict.pop("model")
print(thisdict)
```

-----------------------
----------------------------------------------------

```
Eg2:
# The 'popitem()' method removes the last inserted item (in versions before 3.7, a random item is removed instead):


thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict.popitem()
print(thisdict)
```
--------------------------
-------------------------------------------------
```
Eg3:
# The 'del' keyword removes the item with the specified key name.

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
del thisdict["model"]
print(thisdict)
```

-------------------
--------------------------------------------------------

```
Eg4:
# The del keyword can also delete the dictionary completely.

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
del thisdict
print(thisdict) # this will cause an error because "thisdict" no longer exists.
```

--------------------------
-------------------------------------------------

```
Eg5:
# The clear() method empties the dictionary:

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict.clear()
print(thisdict)
```
