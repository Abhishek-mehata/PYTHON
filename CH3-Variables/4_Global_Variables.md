Python - Global Variables
-------------------------------------------------------------------------------------------------------------------------------------------

```
Global Variables

--Variables that are created outside of a function,loop or any block  are known as global variables.
--Global variables can be used by everyone, both inside of functions or any blocks and outside.

Eg:
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()
# [Note: 'def' keyword is used to create in python]
```


-----------------------------------------------------------------------------------------------------------------

```
--If you create a variable with the same name inside a function, this variable will be local, and can only be used inside the function.

--The global variable with the same name will remain as it was, global and with the original value.

Eg:

x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)
```


---------------------------------------------------------------------------------------------------------------

```
The global Keyword

--Normally, when you create a variable inside a function, that variable is local, and can only be used inside that function.

--To create a global variable inside a function, you can use the 'global' keyword.
--If you use the global keyword, the variable belongs to the global scope.

Eg:

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)
```
--------------------------------------------------------------------------------------------------------------------------------------------------------------

```
You can also, use the global keyword if you want to change the value of a global variable inside a function.

Eg:
x = "awesome"

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)
```


--------------------------------------------------------------------------------------------------------------------------

[**Best of Luck**]