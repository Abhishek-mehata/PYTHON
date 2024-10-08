
Python - Format - Strings
---

```
As we learned in the Python Variables chapter, we cannot combine strings and numbers like this:
age = 36
txt = "My name is John, I am " + age
print(txt)
```
------------------------------------------------------------------------------------------------------------------------
---

But we can combine strings and numbers by using f-strings or the format() method!
---

--------------------------------------------------------------------------------------------------------
---------------

F-Strings
---

```
F-String was introduced in Python 3.6, and is now the preferred way of formatting strings.

To create an f-string in Python, just put an f before your string and use curly braces {} to include variables or expressions right inside the string. It automatically formats the output for you.

A placeholder can contain variables, operations, functions, and modifiers to format the value.

All things inside {} is placeholder.

Eg:
name = "Alice"
age = 25
greeting = f"Hello, my name is {name} and I am {age} years old."
print(greeting)
Output: Hello, my name is Alice and I am 25 years old.
```

------------------------------------------------------------------------------------------------------------------------
---------------

