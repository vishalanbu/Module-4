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
dict1 = {'a': 100, 'b': 200, 'c': 300}
dict2 = {'d': 400, 'e': 500, 'f': 600}

def merge(dict1, dict2):
    merged_dict = {**dict1, **dict2}
    return merged_dict

result = merge(dict1, dict2)

print("Merged Dictionary:")
print(result)
```

## Output


```text
Merged Dictionary:
{'a': 100, 'b': 200, 'c': 300, 'd': 400, 'e': 500, 'f': 600}
```



## Result

Thus, the Python program successfully merges two dictionaries using the dictionary unpacking operator `**`.

