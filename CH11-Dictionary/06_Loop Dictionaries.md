Loop Through a Dictionary
---
```
You can loop through a dictionary by using a 'for' loop.

When you loop through a dictionary, it gives you the keys by default. But there are ways to get the values too.

When you loop through a dictionary, it takes keys for looping.

Eg1:
# Print all key names in the dictionary, one by one
thisdict =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
for x in thisdict:
  print(x)
```

--------------------
----------------------------------------------------

```
Eg2:
# Print all values in the dictionary, one by one
thisdict =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
for x in thisdict:
  print(thisdict[x])
```

--------------------------------------------------------------------------------------------------------------
----------------------------

```
Eg3:
# You can also use the 'values()' method to return/take values of a dictionary while looping

thisdict =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
for x in thisdict.values():
  print(x)
```
--------------------
-----------------------------------------------------

```
Eg4:
# You can use the 'keys()' method to return/take the keys of a dictionary while looping
thisdict =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
for x in thisdict.keys():
  print(x)
```

----------------
-------------------------------------------------------------
```
Eg5:
# Loop through both keys and values, by using the items() method in dictionary
thisdict =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
for x, y in thisdict.items():
  print(x, y)
```
------------------------------------------------------------------------------------------------------------------------------------------------------

