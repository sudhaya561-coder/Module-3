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
Add Code Here
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
## Output
<img width="906" height="268" alt="Screenshot 2025-10-22 212221" src="https://github.com/user-attachments/assets/d8f5247a-5899-4e3c-bbd1-f0d170853ab3" />

## Result
thus,the code runs successfully.
