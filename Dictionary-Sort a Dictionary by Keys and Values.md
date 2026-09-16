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
```python id="f8n2qw"
data = {
    'b': 'banana',
    'd': 'apple',
    'a': 'orange',
    'c': 'grape'
}

print("Original Dictionary:")
print(data)

sorted_by_keys = dict(sorted(data.items()))

print("\nDictionary sorted by keys:")
print(sorted_by_keys)

sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

print("\nDictionary sorted by values:")
print(sorted_by_values)
```

## Sample Output

```text id="j5r7vp"
Original Dictionary:
{'b': 'banana', 'd': 'apple', 'a': 'orange', 'c': 'grape'}

Dictionary sorted by keys:
{'a': 'orange', 'b': 'banana', 'c': 'grape', 'd': 'apple'}

Dictionary sorted by values:
{'d': 'apple', 'b': 'banana', 'c': 'grape', 'a': 'orange'}
```

## Result

Thus, the Python program successfully sorts the dictionary alphabetically by both keys and values.
