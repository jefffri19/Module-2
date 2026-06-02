## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
<img width="475" height="310" alt="image" src="https://github.com/user-attachments/assets/932236ab-0eb0-4d21-bb87-5e049cb50dbd" />

## Output
<img width="302" height="58" alt="image" src="https://github.com/user-attachments/assets/d62a5544-8fb9-433a-885a-83e0daeb54b6" />
<img width="323" height="71" alt="image" src="https://github.com/user-attachments/assets/09d9215d-dcc5-4027-8f0a-13ca436282fa" />


## Result
Thus, the above asked program is encoded and excecuted.
