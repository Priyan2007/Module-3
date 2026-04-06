# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
numbers = [1, 2, 3, 4, 5]

total = sum(numbers)

print(total)
```

## Output
<img width="316" height="153" alt="image" src="https://github.com/user-attachments/assets/ae741eea-e76b-40a0-828c-45c39fdbf00c" />

## Result
Thus the code run successfully!


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
Add code here
```
import re

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print(l1)
```
## Output
<img width="326" height="131" alt="image" src="https://github.com/user-attachments/assets/ddf4f3ca-be34-4abb-a27c-6ea042732d83" />

## Result
Thus the code run successfully!
