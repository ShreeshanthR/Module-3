# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
a = "google"
if a==a[::-1]:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output
<img width="1182" height="192" alt="image" src="https://github.com/user-attachments/assets/1ddae298-4f6b-4a1c-82d9-3717be747139" />

## Result
Thus, the Python program that checks whether the given string is a palindrome without using built-in functions has been successfully created and executed.
