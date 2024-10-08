Python Conditions and If statements
----

```
Python supports given usual logical conditions from mathematics:

Equals:                     a == b

Not Equals:                 a != b

Less than:                  a < b

Less than or equal to:      a <= b

Greater than:               a > b

Greater than or equal to:   a >= b

These conditions can be used in several ways, most commonly in "if statements" and loops.
```

-------------------------------------------------------------------------------------------------
---------------------------------------------

If Statement
---

```
An "if statement" is written by using the "if" keyword.

Eg:
# If statement:
a = 33
b = 200
if b > a:
  print("b is greater than a")
# In this example, we have two variables, a = 33 and b = 200. The if statement checks if b is greater than a. Since 200 is greater than 33, it prints "b is greater than a."
```
-----------------------------------------------------------------------------------------------
-----------------------------------------------

Indentation
---
```
Python uses indentation (spaces at the start of a line) to define code blocks, while other languages often use curly brackets.


Eg:
# 'If' statement, without indentation (will raise an error):            |
a = 33                                                                  |
b = 200                                                                 |
if b > a:                                                               |
print("b is greater than a") # you will get an error                    |
-------------------------------------------------------------------------------------
    |----------------------------------this program will give error due to no indentation
```

----------------------------------------------------------------------------------------------------------------
------------------------------------

Elif(Else if) Statement
---

```
The 'elif' keyword is Python's way of saying "if the previous conditions were not true, then try this condition".

Eg:
a = 33
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")

# In this example, since a equals b, the elif condition is true, so we print 'a and b are equal'
```

--------------------------------------------------------------------------------------------------------------------------
---------------------------------


Else Statement
---
```
The 'else' keyword catches anything which isn't caught by the preceding conditions.
When any of the contitional statements are not true then 'else' statement's code is executed.

Eg:
a = 200
b = 33

if b > a:
  print("b is greater than a")

elif a == b:
  print("a and b are equal")

else:
  print("a is greater than b")

# In this example, a is greater than b, so we skip the first two conditions and print 'a is greater than b' with the else.
```

----------------------------------------------------------------------------------------------------------------
------------------


Short Hand If Statement
---

```
If you have only one statement to execute, you can put it on the same line as the 'if' statement.

Eg:
# One line if statement:
if a > b: print("a is greater than b")
```
-----------------------------------------------------------------------------------------------------------------------------
-----

Short Hand If ... Else Statement
---
```
If you have only one statement to execute, one for if, and one for else, you can put it all on the same line.

Eg:
# One line if else statement
a = 2
b = 330
print("A") if a > b else print("B")
# This technique is known as Ternary Operators, or Conditional Expressions.
```

------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------

Logical Operators
---

```
Operator                        Description                        Example                      Try it

and                             Returns True if all                (x < 5 and  x < 10)          d4.py
                                statements are true



or                              Returns True if one of the          (x < 5 or x < 4)            d4.py
                                statements is true

not                             Reverse the result, returns          not(x < 5 and x < 10)       d4.py
                                False if the result is true
```

------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------

AND
---

```
The 'and' keyword is a logical operator, and is used to combine conditional statements.

Eg:
# Test if 'a' is greater than 'b', AND if 'c' is greater than 'a'
a = 200
b = 33
c = 500
if a > b and c > a:
  print("Both conditions are True")
```
------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------


OR
---
```
The 'or' keyword is a logical operator, and is used to combine conditional statements.

Eg:
# Test if 'a' is greater than 'b' , OR if 'a' is greater than 'c' :
a = 200
b = 33
c = 500
if a > b or a > c:
  print("At least one of the conditions is True")
```
------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------

NOT
```
The 'not' keyword is a logical operator, and is used to reverse the result of the conditional statement.

Eg:
# Test if 'a' is NOT greater than 'b'
a = 33
b = 200
if not a > b:
  print("a is NOT greater than b")
```
------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

Nested If ..... Else statement
---

```
Eg:
#
x = 1

if x > 10:
  print("Above ten,")
  if x > 20:
    print("and also above 20!")
  else:
    print("but not above 20.")
else:
	print("Not greater than 10")
```
------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------

The pass Statement
----
```
When an 'if' statement has no content, use 'pass' to avoid an error.

Eg:
a = 33
b = 200

if b > a:
  pass
# having an empty if statement like this, would raise an error without the pass statement
```

------------------------------------------------------------------------------------------------------------------------------------