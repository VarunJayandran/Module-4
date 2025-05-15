# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```python
import math

class saveetha:
    @staticmethod
    def slot(radius):
        area = math.pi * (radius ** 2)
        return area

try:
    radius = float(input())
    if radius < 0:
        print("Radius cannot be negative.")
    else:
        result = saveetha.slot(radius)
        print(f"Area of circle: {result:.2f}")
except ValueError:
    print("Invalid input. Please enter a numeric value.")
```

## Output

![image](https://github.com/user-attachments/assets/31087e1f-1c67-4e00-a53c-c6db9936b03e)

## Result
Thus,the program has been executed successfully.

---

## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```python
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
```

## Output
![439310420-e8333efb-3f5c-488e-bca7-cb30b9252da2](https://github.com/user-attachments/assets/3ce64350-4aca-4273-9f94-52e3081fd154)

## Result
thus,the program has been executed successfully.

---

# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values


## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order


## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**


## 🧪Program
~~~python
input_dict = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}

sorted_dict = sorted(input_dict.items())

print("Keys and Values sorted in alphabetical order by the key")
for key, value in sorted_dict:
    print(f"({key}, {value})", end=" ")
~~~

## Output
![image](https://github.com/user-attachments/assets/eacf25a7-4788-4500-9f96-dffd8a5a8619)

## Result
Thus,the program has been executed successfully.

---

# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```python
lst=[5, 10, 20]
try:
    print(lst[5])
except IndexError:
    print("You're out of list range")


```

## Output

![image](https://github.com/user-attachments/assets/f69bbc46-ae53-477a-94b1-8c550705a760)

## Result
Thus,the program has been executed successfully.
---

# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
~~~python
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
#driver functions

myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))
~~~

## Output
![439316102-584ecff1-9dfb-4670-b1c8-ee354a85ed3d](https://github.com/user-attachments/assets/6988a86b-a028-43d0-9354-b621b27694c1)

## Result

Thus,the program has been executed successfully.
