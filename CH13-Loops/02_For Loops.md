Python For Loops
---

A 'for' loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

This is not the 'for' loop like  in other programming languages, and works more like an iterator method as found in other object-orientated programming languages.
This works like an iterator method.

With the 'for' loop we can execute a set of statements, once for each item in a list, tuple, set etc.

```
Syntax:
# for i in range(10):
#    # Code to execute

----------------------------------------------

Eg:
# Print each items in a fruit list:
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
```

---------------------------------------------------------------------------------------
------------------------------------------

Looping Through a String
---

```
Even strings are iterable objects, they contain a sequence of characters which can be looped.

Eg:
# Loop through the letters in the word "banana"
for x in "banana":
  print(x)
```

------------------------------------------------------------------------------------------------------
------

Looping Through Dictionary
---
```
Eg:
dict = {
    "name": 'Abhi',
    "class": '10 T',
    "Age": 13,
}

for key, value in dict.items():
    print(key)
    print(value)
```
---
---

The break Statement
---

```
With the 'break' statement we can stop the loop completely even if the 'while loop' condition is true.

With the 'break' statement we can stop the loop before it has looped through all the items.

Eg:
# Exit the loop when x is "banana":
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "banana":
    break
```

------------------------------------------------------------------------------------------------
-----------------

The continue Statement
---
```
With the 'continue' statement we can stop the current iteration of the loop, and continue with the next.

Eg:
# Do not print banana:
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    continue
  print(x)
```

------------------------------------------------------------------------------------------------------------
-----


The range() Function
---

```
To loop through a set of  specified number , we can use the range() function.

----------------------------------------------------
# The range() function generates a sequence of numbers, starting from a specified point (default is 0) and stopping before a specified endpoint, with an optional step value.

# range(5)----------------| This generates numbers from 0 to 4 (5 is excluded).

# range(1, 10, 2)--------------| When you use range(1, 10, 2), it generates a sequence of numbers starting from 1, ending before 10, and increasing by 2 each time.
#      |-------|1 (start)
#      |-------|3 (1 + 2)
#      |-------|5 (3 + 2)
#      |-------|7 (5 + 2)
#      |-------|9 (7 + 2)
-----------------------------------------------------------
```

----
----

```
Eg:
# Using the range() function:
for x in range(6):
  print(x)
# Note that range(6) is not the values of 0 to 6, but the values 0 to 5
```

------------------------------------------------------------------------------------------------------------------
-------------

Nested Loops
---

```
A nested loop is a loop inside a loop.
--The "inner loop" will be executed one time for each iteration of the "outer loop".

Eg:
# Print each adjective for every fruit:

adj = ["red", "big", "tasty"]
fruits = ["apple", "banana", "cherry"]

for x in adj:
  for y in fruits:
    print(x, y)
```

----------------------------------------------------------------------------------------------------------------------
---------
