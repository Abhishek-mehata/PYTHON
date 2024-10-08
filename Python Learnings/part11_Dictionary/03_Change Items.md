Change Values
---

```
You can change the value of a specific item by referring to its key name.

Eg:

# Change the "year" to 2018:
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict["year"] = 2018
```
-----------------------------------------------------------------------------------------------------------------
----------------------------------------------------

Update Dictionary
---

```
The 'update()' method will update the dictionary  with the new items  at the end or overriding existing item from the given argument.
The argument must be a dictionary, or an iterable object with key:value pairs.

Eg:
# Update the "year" of the car by using the update() method:

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict.update({"year": 2020})

# Note:The 'update()' method will update the dictionary with the items from a given argument. If the item does not exist, the item will be added.
```