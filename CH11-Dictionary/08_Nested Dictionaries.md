Nested Dictionaries
---

```
A dictionary can contain dictionaries, this is called nested dictionaries.

Eg:
# Create a dictionary that contain three dictionaries:
myfamily = {
  "child1" : {
    "name" : "Munna",
    "year" : 2004
  },
  "child2" : {
    "name" : "Bujji",
    "year" : 2007
  },
  "child3" : {
    "name" : "Bhairava",
    "year" : 2011
  }
}
```

---------------------------
----------------

Or, if you want to add three different dictionaries into a new dictionary.
---
```
Eg:
# Create three dictionaries, then create one dictionary that will contain the other three dictionaries
child1 = {
  "name" : "Munna",
  "year" : 2004
}
child2 = {
  "name" : "Bujji",
  "year" : 2007
}
child3 = {
  "name" : "BHairava",
  "year" : 2011
}

myfamily = {
  "child1" : child1,
  "child2" : child2,
  "child3" : child3
}
```

---------------------------------------------------------------------------------------------------------------------------------------
-----------------------

Access Items in Nested Dictionaries
---
```
To access items from a nested dictionary, you use the name of the dictionaries, starting with the outer dictionary.

Eg:
# Print the name of child 2
myfamily = {
  "child1" : {
    "name" : "Munna",
    "year" : 2004
  },
  "child2" : {
    "name" : "Bujji",
    "year" : 2007
  },
  "child3" : {
    "name" : "Bhairava",
    "year" : 2011
  }
}

print(myfamily["child2"]["name"])
```

----------------------------------------------------------------------------------------------------------------------------
------------------------------------------

Loop Through Nested Dictionaries
---

```
You can loop through a dictionary by using the 'items()' method like this:

Eg:
# Loop through the keys and values of all nested dictionaries
myfamily = {
  "child1" : {
    "name" : "Emil",
    "year" : 2004
  },
  "child2" : {
    "name" : "Tobias",
    "year" : 2007
  },
  "child3" : {
    "name" : "Linus",
    "year" : 2011
  }
}

for x, obj in myfamily.items():
    print(x)
    
    for y in obj:
        print(y + ':', obj[y])
```        
----------------------------------------------------------------------------------------------------------------------------------------------------------------------