# Ex. No: 16A - Constructing and Printing an AVL Tree in Python

## AIM:
To write a Python program to construct an **AVL tree** and print the nodes of it using the appropriate packages and built-in function.
### Name-Ranjith Ganesh B.
### Reg No-212223060222
---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a function `getDictTree(tree)` to return the **dict_tree** of an AVL tree.

**Step 3**: Define a function `Construct_AVL(L)` to:
- Create an **AVL tree** from the list `L`.
- Get and print the **dict_tree** using `getDictTree(tree)`.

**Step 4**: Define a list `L` with integer values.

**Step 5**: Call `Construct_AVL(L)` to build the tree and print the result.

**Step 6**: End the program.

---

## PYTHON PROGRAM
```
from TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print(getDictTree(tree))

L=[12,8,18,5,11,17,4,7,2]

```

## OUTPUT
![image](https://github.com/user-attachments/assets/ccc6a172-ce3f-4e21-bc18-670d43fa2739)


## RESULT
Thus,Python program to construct an AVL tree and print the nodes of it using the appropriate packages and built-in function was successfully implemented and verified.
