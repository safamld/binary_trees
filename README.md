0x1D. C - Binary trees


A binary tree is a data structure composed of nodes, where each node contains a value and at most two child nodes, referred to as the left child and the right child. The structure resembles a tree, with the root node at the top and branches extending downwards.

In a binary tree:

Each node can have at most two children, referred to as the left child and the right child.
The left child is smaller than the parent node, and the right child is greater than or equal to the parent node in a binary search tree (BST). However, in a general binary tree, this ordering might not be strictly followed.
Nodes without children are called leaf nodes.
The height of the tree is the maximum number of edges from the root node to a leaf node.
Binary trees are widely used in computer science for various applications, including implementing binary search trees, representing expressions in arithmetic expressions, constructing hierarchical data structures, and more. They offer efficient search, insertion, and deletion operations when properly balanced, making them a fundamental building block in many algorithms and data structures.

Functions to print binary trees in a pretty way

                           .----------------------(006)-------.
                      .--(001)-------.                   .--(008)--.
                 .--(-02)       .--(003)-------.       (007)     (009)
       .-------(-06)          (002)       .--(005)
  .--(-08)--.                           (004)
(-09)     (-07)
