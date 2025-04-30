## Dictionary Operations in Python: Merging Two Dictionaries
# NAME: GOKUL SHARAN R
# REG NO: 212223040052

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```
## Output
![image](https://github.com/user-attachments/assets/596dc28d-02ed-4f4b-962d-cb0233a855f3)
![image](https://github.com/user-attachments/assets/6e4ac66d-2f88-4b0d-ace6-0fc175ca8536)



## Result
Thus the program executed successfully.
