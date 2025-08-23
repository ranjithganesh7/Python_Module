# Ex. No: 16B - Constructing and Balancing an AVL Tree in Python

## AIM:
To write a Python program to construct an **AVL tree**, balance it, and print the nodes **before and after balancing** using the appropriate packages and built-in function.
### Name-Ranjith Ganesh B.
### Reg No-212223060222
---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a method `getDictTree(tree)` to return the `dict_tree` or structure of the AVL tree.

**Step 3**: Define a method `Construct_AVL(L)` to:
- Create a binary tree from the list `L`.
- Print the tree **before balancing**.
- Sort and reinsert the nodes in a balanced manner (simulating AVL behavior).
- Print the tree **after balancing**.

**Step 4**: Create a list `L` of integers.

**Step 5**: Call `Construct_AVL(L)` to build and balance the tree.

**Step 6**: End the program.

---

## PYTHON PROGRAM
```
from TreeAVL.AVL import AVL
def getDictTree(self):
    return self.dict_tree
def Construct_AVL(L):
    tree=AVL(L)
    print(getDictTree(tree))
L=[12,8,18,5,11,17,4,7,2]
```

## OUTPUT
![image](https://github.com/user-attachments/assets/4ea5ec7c-efa6-412a-aa4c-bf261ee5e6d4)


## RESULT
 Thus, Python program to construct an AVL tree, balance it, and print the nodes before and after balancing using the appropriate packages and built-in function was successfully implemented and verified.
