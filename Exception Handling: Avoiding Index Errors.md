# Exception Handling in Python: Avoiding Index Errors

## Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## Program
```
msg="You're out of list range"
lst=[5, 10, 20]
try:
print(lst[5])
except:
print(msg)

```
## Output
<img width="652" height="158" alt="image" src="https://github.com/user-attachments/assets/3702616b-847d-441d-8763-01692d0bb0a7" />

## Result
Thus, the program to handle exceptions and avoid index errors in Python was executed successfully
