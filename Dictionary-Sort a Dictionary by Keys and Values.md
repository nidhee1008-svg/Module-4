# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. Start the program.
2. Define a dictionary with key-value pairs.
3. Sort by keys using `sorted(dictionary.items())`.
4. Convert the sorted result to a dictionary using `dict()`.
5. Sort by values using `sorted(dictionary.items(), key=lambda item: item[1])`.
6. Convert the sorted result to a dictionary using `dict()`.
7. Display the original dictionary and sorted dictionaries.
8. End the program.

---

## 🧪 Program

```python
dictionary = {'banana': 3, 'apple': 5, 'cherry': 1, 'date': 4}

sorted_by_keys = dict(sorted(dictionary.items()))
sorted_by_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))

print("Original dictionary:", dictionary)
print("Sorted by keys:", sorted_by_keys)
print("Sorted by values:", sorted_by_values)
```

## Sample Output

```text
Original dictionary: {'banana': 3, 'apple': 5, 'cherry': 1, 'date': 4}
Sorted by keys: {'apple': 5, 'banana': 3, 'cherry': 1, 'date': 4}
Sorted by values: {'cherry': 1, 'banana': 3, 'date': 4, 'apple': 5}
```

## Result

Thus, the Python program to sort a dictionary by keys and values was executed successfully.
