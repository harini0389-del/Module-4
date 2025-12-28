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

---

## 🧪Program
```
input_tuples = [(2,56),(1,2),(5,12),(4,24),(6,18),(3,323)]

my_dict = dict(input_tuples)

sorted_items = sorted(my_dict.items())

print("Keys and Values sorted in alphabetical order by the key")
print(*sorted_items)
```
## Sample Output

<img width="1143" height="127" alt="image" src="https://github.com/user-attachments/assets/5dda597d-f11e-4895-92a7-420dc1bb64a9" />

## Result
Thus, the program has been successfully executed.
