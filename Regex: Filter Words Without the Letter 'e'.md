# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result = []
for item in items:
    if not re.search(r'e', item):
        result.append(item)
print(result)
```
## Output
<img width="817" height="189" alt="md32" src="https://github.com/user-attachments/assets/888d123e-3a9c-434d-b73e-987288761fee" />

## Result
Thus To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) is executed successfully.

