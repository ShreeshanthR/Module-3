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
```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1=[item for item in items if not re.search(r"e",item)]
print(l1)
```
## Output
<img width="891" height="435" alt="image" src="https://github.com/user-attachments/assets/a7c8841c-9b8a-41dd-90b8-76f6413c47f9" />

## Result
Thus, the Python program that filters and displays all words not containing the letter 'e' using regular expressions has been successfully created and executed.
