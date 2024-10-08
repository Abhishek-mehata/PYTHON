<!-- 2String_slicing.md -->

Python - Slicing Strings
---

```
Suppose you have a string data 'Radhe Shyam' in variable x. You need only 'Shyam' from variable x, then you can use Slicing concept in python.



Slicing in python returns a  string data from already existing string data.

In python string slicing we have to Specify the slicing starting index and the [ending index+1], separated by a colon, to return a part of the string.

The indexing in string starts always from 0. (Eg: In x='Radhe' , x[0] will be 'R' , x[1] will be 'a' )



Syntax for String Slicing:

string[start_index : end_index]
```

---------------

```
Example:

# Get the characters from position 2 to position 4  (5 not included)

b = "Hello World!"

print(b[2:5]) # Output: 'llo'

# Note: The first character has index 0.
```

-------------------------------------------------------------------------------------------------------------------------
---

Slice From the Start
---

```
By leaving out the start index, the slicing  will start from the first character.

Eg:

# Get the characters from the start[0] to position 4 ( 5 not included):

b = "Hello World!"

print(b[:5]) #Output: Hello
```


-----------------------------------------------------------------------------------------------------------------------------
---

Slice To the End
---
```
By leaving out the end index, the slicing will go to the end.

Eg:

# Get the characters from position 6, and all the way to the end

b = "Hello World!"

print(b[6:]) #Output:World!
```

--------------------------------------------------------------------------------------------------------------------
---

Negative Indexing
---

```
we can use negative indexes to start the slice from the end of the string.

Eg:

b = "Hello, World!"  # This is the string that we will be slicing.

print(b[-5:-2])  # Output: "orl"

# We are using negative indexing to slice the string.

# -5 refers to the fifth character from the end (which is 'o').

# -2 refers to the second character from the end (which is 'd'), but not included: "d" in "World!" (position -2).
```

----------------------------------------------------------------------------------------------------------------------------------
[**Best of Luck**]