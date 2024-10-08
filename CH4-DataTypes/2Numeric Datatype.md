Python Numbers
----

There are three numeric types in Python:

int

float 

complex

----------------------------------------------------------------------------------------------------------------------

```
[Variables of numeric types are created when you assign a value to them]

Eg:
x = 1

y = 2.8

z = 1j

print(type(x))

print(type(y))

print(type(z))
```


------------------------------------------------------------------------------------------------------------------------------------------

Int
---

```
Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length.

Eg:

x = 1

y = 35656222554887711

z = -3255522

print(type(x))

print(type(y))

print(type(z))
```


----------------------------------------------------------------------------------------------------------------

Float
---

```
Float, or "floating point number" is a number, positive or negative, containing one or more decimals.

Eg:

x = 1.10

y = 1.0

z = -35.59


print(type(x))

print(type(y))

print(type(z))
```

---------------------------------------------------------------------------------------------------------------------------

Complex
---

```
Complex numbers are written with a "j" as the imaginary part

Eg:

x = 3+5j

y = 5j

z = -5j


print(type(x))

print(type(y))

print(type(z))
```

----------------------------------------------------------------------------------------------------------------------------------

Type Conversion
---

```
You can convert from one data type to another with the int(), float(), and complex() methods.

Eg:

#convert from int to float:

x = float(1)

#convert from float to int:

y = int(2.8)

#convert from int to complex:

z = complex(1)

print(x)

print(y)

print(z)


print(type(x))

print(type(y))

print(type(z))

[Note: You cannot convert complex numbers into another number type.]
```

-----------------------------------------------------------------------------------------------------


-------------------------------------------------------------------------------------------------

Random Number
---


```
Python does not have a 'random()' function to make a random number, but Python has a built-in module called 'random' that can be used to make random numbers.

Module is a python file where a set of functions are already coded and we can just call those functions without creating or defining them by our own.

Eg:

#Import the random module, and display a random number between 1 and 9

import random
print(random.randrange(1, 10))
```

---------------------------------------

