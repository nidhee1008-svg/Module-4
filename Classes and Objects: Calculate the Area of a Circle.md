# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. Get the radius of the circle as input from the user.
2. Create a class named `cse`.
3. Inside the class, define a method named `mech` to calculate the area of the circle using the formula:
   `Area = pi * r * r`
4. Create an object of the class.
5. Call the method with the radius value.
6. Print the area of the circle.

## 🧾 Program

```python
class cse:
    def mech(self, r):
        area = 3.14 * r * r
        print("Area of circle:", area)

r = float(input("Enter radius: "))

obj = cse()
obj.mech(r)
```

## Output

```text
Enter radius: 5
Area of circle: 78.5
```

## Result

Thus, the Python program to calculate the area of a circle using class and object was executed successfully.
