# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
# Reg.No-212223060222
# Name-Ranjith Ganesh B.

n = eval(input())
a = []
for i in range(1, n):
    if i % 9 == 0:
        a.append(i)
b = tuple(a)
print(b)
print("Length of the tuple is", len(a))

```

### OUTPUT
![image](https://github.com/user-attachments/assets/419d0b97-f0c3-4868-a1d5-3fdff90f89e6)


### RESULT
Thus the program to create a tuple of multiples of 9 up to N and print the tuple and its length has been implemented and executed successfully.
