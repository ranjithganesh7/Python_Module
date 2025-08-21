# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
# Reg.No-212223060222
# Name-Ranjith Ganesh B.

import re
str = input()
patterns = 'ab{2,3}?'

if re.search(patterns, str):
    print("Found a match!")
else:
    print("Not matched!")


```
### OUTPUT
![image](https://github.com/user-attachments/assets/92c10b5d-199d-4cf8-ba46-74352aa585aa)


### RESULT
Thus the program matches a string containing an 'a' followed by two to three 'b' characters using regular expressions has been implemented and executed successfully.
