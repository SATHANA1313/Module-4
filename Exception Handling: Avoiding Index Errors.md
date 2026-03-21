# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
lis=[5, 10, 20]
try:
    print(lis[5])
except:
    print("You're out of list range")
```

## Output

<img width="625" height="163" alt="Screenshot 2025-11-13 092933" src="https://github.com/user-attachments/assets/dde902f4-fec8-4a96-8b61-d93f570f4a59" />


## Result

Thus the python program has been executed successfully.
