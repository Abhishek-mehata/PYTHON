List Comprehension
---

```
--List comprehension offers a shorter syntax when you want to create a new list based on the values of an existing list.

Example:
Based on a list of fruits, you want a new list, containing only the fruits with the letter "a" in the name.
```
------------------
------------------
```
Example1:
# Without list comprehension you will have to write a for statement with a conditional test inside
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = []

for x in fruits:
  if "a" in x:
    newlist.append(x)
print(newlist)
```
------------------
------------------
```
Example2:
# With list comprehension you can do all that with only one line of code
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
           
newlist = [x for x in fruits if "a" in x]
print(newlist)
```

------------------
------------------

Syntax for List Comprehension
---

```
newlist = [expression for item in iterable if condition == True]

# 'expression' is the value which will be returned as value for new list;
# 'for' is just a normal for loop
# 'item' is just representation of iterable[list,tuple,set,dictionary].
# 'iterable' is list for list comprenhension.



# The return value is a new list, leaving the old list unchanged.
```

-------------------------------------------------------------------------------------------------------------------------------------
---------------------------------


Condition
---

```
The condition is like a filter that only accepts the items that validate to True .

                                                      |------------------Condition
                                           |--------------------|
newlist = [expression for item in iterable (if condition == True) ]

Eg1:
# Only accept items that are not "apple"
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = [x for x in fruits if x != "apple"]

# The condition if x != "apple"  will return True for all elements other than "apple", making the new list contain all fruits except "apple".
```
--------------------------------------------------------------------------
--------------------------------------------------------------------------

```
The condition is optional and can be omitted/overwriten.

Eg2:
# With no 'if' statement,
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = [x for x in fruits]
```

--------------------------------------------------------------------------------------------------------------------------------
--------------------------------------

Iterable
----
```
The iterable can be any iterable object like a list, tuple , set , dictionary etc.

                                      |--------------------Iterable
                                  |-------|
newlist = [expression for item in iterable  if condition == True]

Eg1:
# You can use the range() function to create an iterable:
newlist = [x for x in range(10)]

----------------------------------------------------------------------

Eg2:
# Same example, but with a condition
newlist = [x for x in range(10) if x < 5]
```

-------------------------------------------------------------------------------------------------------------------------------------------
---------------------------

Expression
---

```
When you loop through items, each item goes through some processing, and the result of that processing becomes part of the new list.

              |-------------------Expression
            |----------|
newlist = [  expression  for item in iterable if condition == True]
Eg1:
# Set the values in the new list to upper case
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = [x.upper() for x in fruits]

--------------------------------------------------------------------------

You can set the outcome to whatever you like by the help of expression

Eg2:
# Set all values in the new list to 'hello'
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = ['hello' for x in fruits]
```

-----------------
-----------------------------------------------------------------
```
The expression can also contain conditions, not like a filter, but as a way to manipulate the outcome:

Eg3:
# Return "orange" instead of "banana":
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = [(x if x != "banana" else "orange") for x in fruits]
# "Return the item if it is not banana, if it is banana return orange".
```

--------------------------------------------------------------------------------------------------------------------------
```

          **********  EXERCISE **********

          _____      |        |   ______
          |            |    |    | 
          |___           |       |______ 
          |            |    |    |            .
          |_____    |          | |________  . . .


          **********  EXERCISE **********


          [Guess output of all 'newlist' iterable's]


            fruits = ["apple", "banana", "cherry", "kiwi", "mango"]

            # newlist = [x for x in fruits if x != "apple"]

            # newlist = [x for x in fruits]

            # newlist = [x for x in range(10)]

            # newlist = [x for x in range(10) if x < 5]

            # newlist = [x.upper() for x in fruits]

            # newlist = [x+'hello' for x in fruits]

            # newlist = [x if x != "banana" else "orange" for x in fruits]

            print(newlist)

            # newlist = [expression for item in iterable if condition == True]

```

--------------------------------------------------------------------------------------------------------------------------
[**Best of Luck**]


