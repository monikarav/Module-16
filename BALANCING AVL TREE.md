# Exp No : 20


## Aim
To Write a Python program to construct an AVL tree and Print the nodes of it using the appropriate packages and built in function.

## Algorithm

1. Start the program.
   
2. Import AVL Class: Import the AVL class from the TreeAVL.AVL module.

3. Define getDictTree Method: Create a method getDictTree(self) that returns the internal dictionary representation of the AVL tree.

4. Define Construct_AVL Function: Define a function Construct_AVL(L) to create and display the AVL tree.

5. Create AVL Tree: Inside Construct_AVL, initialize an AVL tree object tree with list L as input.

6. Build Tree with Insertions: The AVL class inserts elements from the list L into the tree, balancing it after each insertion.

7. Get Tree Structure: Call getDictTree(tree) to retrieve the internal dictionary/tree structure.

8. Print Tree: Display the AVL tree structure using print.

9. Stop the program.

## Program

```
from  TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
    tree=AVL(L)
    print(getDictTree(tree))
    
L=[10, 5, 15, 7, 18, 9]
```

## OUTPUT

![image](https://github.com/user-attachments/assets/54e30a4a-d9c1-46aa-8773-4dad10028080)

## RESULT

Thus the Write a Python program to construct an AVL tree and Print the nodes of it using the appropriate packages and built in function was successfully implemented.
