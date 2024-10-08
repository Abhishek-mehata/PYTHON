Change Item Value
---

```
--To change the value of a specific item, use  the index number.

Eg:

# Change the second item:
thislist = ["apple", "banana", "cherry"]
thislist[1] = "blackcurrant"
print(thislist)
```

------------------------------------------------------------------------------------------------------
---------------

Change value of a Range of Items
---

```
Eg:

# Change the values "banana" and "cherry" with the values "blackcurrant" and "watermelon" respectively.
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "mango"]
thislist[1:3] = ["blackcurrant", "watermelon"]
print(thislist)
```

-----------------------------------------------------------------------------------------------------------------------
-----------------------


```
Note:If you add more items than you take out, the new items will go where you put them, and the other items will shift to make room.

Imagine you have a row of books on a shelf. If you remove one book and then put two books in its place, those two books will fit in where the first book was, and the rest of the books will slide over to make space for the extra book.

This is the same idea: if you add more things than you remove, the new things go where you want, and everything else moves over to make room.

Eg:

# Change the second value by replacing it with two new values
thislist = ["apple", "banana", "cherry"]
thislist[1:2] = ["blackcurrant", "watermelon"]
print(thislist)

# Note:The list will get longer or shorter if you add more items than you remove, or remove more items than you add.
```

------------------------------------------------------------------------------------------------------------------------------

```
If you insert less items than you replace, the new items will be inserted where you specified, and the remaining items will move accordingly.

Eg:

# Change the second and third value by replacing it with one value
thislist = ["apple", "banana", "cherry"]
thislist[1:3] = ["watermelon"]
print(thislist)
```

----------------------------------------------------------------------------------------------------------------------
---------------------


Insert Items
---

```
To insert a new list item, without replacing any of the existing values, we can use the insert() method.
The insert() method inserts an item at the specified index.

Eg:

# Insert "watermelon" as the third item
thislist = ["apple", "banana", "cherry"]
thislist.insert(2, "watermelon")
print(thislist)
```

---
[**Best of Luck**]