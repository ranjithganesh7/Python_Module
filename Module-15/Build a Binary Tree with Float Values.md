# Ex. No: 15A - Build a Binary Tree with Float Values

## AIM:
To write a Python program to build a binary tree with a root, left, and right node using floating-point values.
### Name-Ranjith Ganesh B.
### Reg No-212223060222
---

## ALGORITHM:

1. **Start the program.**
2. **Import** the `Node` class from the `binarytree` module.
3. **Create a root node** using the `Node` class and assign a floating-point value.
4. **Create left and right child nodes** for the root with float values.
5. **Convert the tree** to a list and print the list of nodes.
6. **End the program.**

---

## PYTHON PROGRAM

```
from binarytree import Node
def _build_bst_from_sorted_values(sorted_values):
    if len(sorted_values)==0:
        return None
    mid=len(sorted_values)//2
    root=Node(sorted_values[mid])
    root.left=_build_bst_from_sorted_values(sorted_values[:mid])
    root.right=_build_bst_from_sorted_values(sorted_values[mid+1:])
    return (root)
def insert_BST(val):
    global a
    if val in a:
        return False
    else:
        a.append(val)
        tree=_build_bst_from_sorted_values(sorted(a))
        return tree
def display(T):
    for i in T.values:
        print(i,"-->",end="")
a=[3,1,4,2]  
val=int(input())
print("BST before insertion:")
bst=_build_bst_from_sorted_values(sorted(a))
display(bst)
t1=insert_BST(val)
print("\nBST after insertion:")
display(t1)

```

## OUTPUT
![image](https://github.com/user-attachments/assets/115621cb-cc3d-42f2-bd22-aa0ca47de415)


## RESULT
Thus the Python program to build a binary tree with a root, left, and right node using floating-point values was successfully implemented and verified.
