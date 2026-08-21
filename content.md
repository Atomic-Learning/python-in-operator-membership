The `in`{.python} operator checks whether a value is contained within a collection (such as a string or list) and returns `True`{.python} or `False`{.python}. We'll use strings and lists for examples here.

# Checking for Items in Lists

With lists, `in`{.python} checks whether an item list on the right of the operator has the same value as the value on the left of the operator:

```py-cell
a = 1
list1 = [1, 2, 3]
list2 = [4, 5, 6]

print(a in list1)
print(2 + 1 in list1)
print(4 in list2)
print(1 in list2)
```

# Checking for Substrings in Strings

With strings, `in`{.python} checks whether one string is a substring of another:

```py-cell
print("fun" in "fundamentals")
print("fun" in "skipping ahead")
```

# The not in Operator

You can use `not in`{.python} to check if a value is **not** contained in a collection:

```py-cell
list1 = [1, 2, 3]
print(2 not in list1)
print("xyz" not in "hello")
```
