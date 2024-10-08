Python - Access Dictionary Items

---

Accessing Items
---
```
You can access the items of a dictionary by referring to its key name, inside square brackets

Eg:
# Get the value of the  key named "model"
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
x = thisdict["model"]
```
----
---------------------------------------------------

There is also a method called 'get()' that will give you the same result.
---

```
Eg:
# Get the value of the  key named "model"
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
x = thisdict.get("model")
print(x)
```

----------------------------------------------------------------------------------------------
-----------------------------


Get all  Keys
---

```
The 'keys()' method will return a list of all the keys in the dictionary.

Eg:
# Get a list of the keys:
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
x = thisdict.keys()
print(x)
```

----------
-----------------------------------------------------------------------------------------------------------------

Note:
---

```
# The list of the keys is a view of the dictionary, meaning that any changes done to the dictionary will be reflected in the keys list.

Eg:
# Add a new item to the original dictionary, 
# and see that the keys list gets updated as well
car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}
x = car.keys()
print(x) # before the change
# Adding new key and value in dictionary
car["color"] = "white"
print(x) #after the change
```

-----------------------------------------------------------------------------------------------------------
----------------

Get all Values
---

```
The 'values()' method will return a list of all the values in the dictionary.

Eg:
# Get a list of the values:

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}

x = thisdict.values()

print(x)
```


-----------
----------------------------------------------------------------
Note:
---

```
The list of the values is a view of the dictionary, meaning that any changes done to the dictionary will be reflected in the values list.

Eg1:
# Make a change in the original dictionary, and see that the values list gets updated as well:
car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}

x = car.values()
print(x) #before the change
car["year"] = 2020
print(x) #after the change

----------------------------------------------------------------------------------------------------------

Eg2:
# Add a new item to the original dictionary, and see that the values list gets updated as well:

car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}

x = car.values()

print(x) #before the change

car["color"] = "red"

print(x) #after the change
```


-------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------

Get Items
---

```
The 'items()' method will return each item in a dictionary, as tuples in a list.

Eg:
# Get a list of the key:value pairs
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}

x = thisdict.items()

print(x)
```

-----
-------------------------------------------------------

Note:
---

```
The returned list is a view of the items of the dictionary, meaning that any changes done to the dictionary will be reflected in the items list.

Eg1:
# Make a change in the original dictionary, and see that the items list gets updated as well:
car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}

x = car.items()
print(x) #before the change
car["year"] = 2020
print(x) #after the change
---------------------------------------------------------------------------------------------------
Eg2:
# Add a new item to the original dictionary, and see that the items list gets updated as well:
car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}

x = car.items()
print(x) #before the change
car["color"] = "red"
print(x) #after the change
```
------------------------------------------------------------------------------------------------------------------------------------
------------

Check if Key Exists
---

```
To determine if a specified key is present in a dictionary use the 'in' keyword.

Eg:
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
if "model" in thisdict:
  print("Yes, 'model' is one of the keys in the thisdict dictionary")
```
------------------------------------------------------------------------------------------------------------------------------------------------

