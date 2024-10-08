Python Loops:
---

Python has two primitive loop commands:

1]  'while' loops

2]  'for' loops

----------------------------------------------------------
------------------------------------------------

The while Loop
---

```
With the while loop we can execute a set of statements as long as a condition is true.

Syntax:
# while condition:
#    # code block to be executed repeatedly

---------------------------------------------------

Eg:
# Print i as long as i is less than 6
i = 1
while i <= 6:
  print(i)
  i += 1
# Note: remember to increment[increase by one] 'i' to make condition false when 'i' will be greater than 6, or else the loop will continue forever.

# The while loop needs variables to be initialized first; here, we set 'i' to 1 as the indexing variable
```

------------------------------
----------------------------------------------------------------------------

The break Statement
---

```
With the 'break' statement we can stop the loop completely even if the 'while loop' condition is true.

Eg:
# Exit the loop completely when i becomes 3
i = 1
while i < 6:
  print(i)
  if (i == 3):
    break
  i += 1
```

--------------------------------------------------------------------------------------
--------------------

The continue Statement
---

```
The 'continue' statement in Python is used to skip the loop body for the current turn and jump to the next turn in the loop.

The continue statement skips the current loop iteration and moves to the next iteration.

Eg:
# Continue to the next iteration when 'i' is 3 by skipping the iteration[loop body] for i=3:
i = 0
while i < 6:
  i += 1
  if i == 3:
    continue
  print(i)

# Note that number 3 will be missing in the result.
```
---------------------------------------------------------------------------------------------------------------------------------------------



