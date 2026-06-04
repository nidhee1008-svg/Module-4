# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a `try-except` block.
3. In the `try` block, attempt to access an index that is out of range.
4. In the `except` block, catch the `IndexError`.
5. Print a custom message if the index is out of range.

## 🧾 Program

```python
list1 = [10, 20, 30, 40, 50]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```

## Output

```text
You're out of list range
```

## Result

Thus, the Python program to handle an IndexError was executed successfully.
