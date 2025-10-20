# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

numbers = [10, 20, 30, 40, 50]
total = sum(numbers)
print(total)

## Output

<img width="1573" height="147" alt="Screenshot 2025-10-20 200600" src="https://github.com/user-attachments/assets/ef22a8d3-f57e-4509-ae38-d30bfb11a308" />

## Result

Thus To write a Python program that calculates the **sum of all elements** in a list.
Hence the code has been executed successfully.

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

import re

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print(l1)

## Output

<img width="1567" height="283" alt="Screenshot 2025-10-20 200955" src="https://github.com/user-attachments/assets/e0bfc149-dfb5-4161-b6de-d5888ebea6fd" />

## Result

Thus To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.
Hence the code has been executed successfully.

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program

def remove(s):
    n = int(input("Enter the index to remove: "))
    a = ""
    for i in range(len(s)):
        if i != n:
            a += s[i]
    return a

input_string = input("Enter a string: ")
result = remove(input_string)
print("Modified string:", result)

## Output

<img width="1578" height="316" alt="Screenshot 2025-10-20 201315" src="https://github.com/user-attachments/assets/cb035f27-6634-4136-a1c4-5a35c5b836aa" />

## Result

Thus To write a Python program that accepts a string and removes the character at a specified index.
Hence the code has been executed successfully.

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

s = "google"
reversed_s = s[::-1]

if s == reversed_s:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")

## Output

<img width="1523" height="211" alt="Screenshot 2025-10-20 201550" src="https://github.com/user-attachments/assets/1eaca42b-717a-4903-976d-3f1e870d4daf" />

## Result

Thus To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.
Hence the code has been executed successfully.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program

x = ('a', 'b', 'n', 5, 8, 3)

print('n' in x)
print(8 in x)

## Output

<img width="1532" height="172" alt="Screenshot 2025-10-20 201745" src="https://github.com/user-attachments/assets/8adc3261-b01b-4911-8bb3-604f4dd99500" />

## Result

Thus To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.
Hence the code has been executed successfully.

