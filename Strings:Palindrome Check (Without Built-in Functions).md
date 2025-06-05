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

```python

org="google"
dup=org[::-1]
if(dup==org):
    print("string is a plaindrome")
else:
    print("string is not a plaindrome")

```

## Output

![image](https://github.com/user-attachments/assets/5675cf7c-9422-42e6-b5f5-926b9f663904)

## Result

Thus implemented the python program to check whether the string "google" is a plaindrome or not, without using built in palindrome checking functions.
