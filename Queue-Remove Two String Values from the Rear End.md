# Queue-Remove Two String Values from the Rear End in Python 🧵

This Python program demonstrates how to manage a list of strings and remove the last two elements (i.e., from the rear of the list).

## 🎯 Aim

To write a Python program to:
- Accept `n` string values from the user
- Remove the last two values (rear end of the list)
- Display the updated list

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` from the user (number of strings).
3. Loop `n` times:
   - Read a string input.
   - Append it to the list `q`.
4. Remove the last element using `pop()`.
5. Remove the next last element using `pop()` again.
6. Display the updated list.

##  Program:
```
from collections import deque
a=deque()
n=int(input())
for i in range(n):
    a.append(input())
a.popleft()
a.popleft()
print(a)
```

### Output:
<img width="1077" height="447" alt="image" src="https://github.com/user-attachments/assets/2c0f2f4f-cfba-433f-a5e1-bf5ce151f19f" />

## Result:
Thus,the program is executed successfully
