# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in read mode.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file.
4. Check if the first character of the line is not `'T'`.
5. If the line does not start with `'T'`, increment `count` by 1.
6. Print the count value.

## 🧾 Program

```python
count = 0

file = open("story.txt", "r")

for line in file:
    if line[0] != 'T':
        count = count + 1

file.close()

print("Number of lines not starting with T:", count)
```

## Output

```text
Number of lines not starting with T: 3
```

## Result

Thus, the Python program to count lines not starting with 'T' was executed successfully.
