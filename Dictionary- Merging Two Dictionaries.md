# Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
3. Store the merged dictionary in a variable.
4. Print the merged dictionary.

## 🧾 Program

```python
dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}

def merge(dict1, dict2):
    return {**dict1, **dict2}

merged_dict = merge(dict1, dict2)

print("Merged dictionary:", merged_dict)
```

## Output

```text
Merged dictionary: {'a': 1, 'b': 2, 'c': 3, 'd': 4}
```

## Result

Thus, the Python program to merge two dictionaries was executed successfully.
