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

Add code here
def palindrome(a):
    x1=a[::-1]
    if a==x1:
       print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
    
        
        
string =input()
palindrome(string)
## Output
<img width="1033" height="161" alt="Screenshot 2025-10-22 212421" src="https://github.com/user-attachments/assets/74c19c08-8c38-4fd3-9d55-3396b44c7e6a" />

## Result
thus,the code runs successfully.
