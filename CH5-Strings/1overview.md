Python Strings
---

```
Strings in python are surrounded by either single quotation marks, or double quotation marks.

'hello' is the same as "hello".

You can also display strings using print() or directly store it on variable.

Eg:
x="Hello"
print(x)
print('Hello')
```

----------------------------------------------------------------------------------------------------

Quotes Inside Quotes
---
```
You can use quotes inside a string if they don't match the surrounding ones.


Eg:
print("It's alright")
print("He is called 'Johnny'")
print('He is called "Johnny"')
```


------------------------------------------------------------------------------------------------------------

Multiline Strings
---
```

You can assign a multiline string to a variable by using three quotes.

Eg1:

a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""

print(a)
---------------------------------------------
Eg2:

a = '''Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.'''

print(a)

[Note: in the result, the line breaks are inserted at the same position as in the code.]

```


-------------------------------------------------------------------------------------------------------------
Strings are Arrays
---
```

Like many other popular programming languages, strings in Python are arrays of bytes representing unicode characters.

However, Python does not have a character data type, a single character is simply a string with a length of 1.

Square brackets can be used to access elements of the string.

Eg:
Get the character at position 1 (remember that the first character has the position 0)

a = "Hello, World!"
print(a[0])
```

----------------------------------------------------------------------------------------------------------------

Looping Through a String
---

```
Since strings are arrays, we can loop through the characters in a string, with a for loop.

Eg:
Loop through each letters in the word "banana":

for x in "banana":
    print(x)
```

-----------------------------------------------------------------------------------------------------------------------

String Length
---
```
To get the length of a string, use the len() function.

Eg:
a = "Hello, World!"
print(len(a))
```

-----------------------------------------------------------------------------------------------------------------
[**Best of Luck**]