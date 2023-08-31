**Binary Tree Learning Project**

This repository contains resources and solutions for a learning project focused on binary trees and related concepts. The project aims to provide a clear understanding of binary trees, binary search trees, their differences, traversal methods, and various types of binary trees. By completing this project, you will be able to explain these concepts to others without relying on external references.

## Description

A binary tree is a data structure that consists of nodes, with each node having at most two children: a left child and a right child. This hierarchical structure is widely used in computer science to efficiently manage and manipulate data. Binary trees offer advantages for insertion, deletion, and searching operations. Binary search trees, a specific type of binary tree, are particularly useful for maintaining sorted data and enabling efficient search algorithms.

## Learning Objectives

By the end of this project, you should be able to:

- Define what a binary tree is and distinguish it from a binary search tree.
- Explain the time complexity advantages of binary trees compared to linked lists.
- Describe the concepts of depth, height, and size in a binary tree.
- Identify and utilize various methods for traversing a binary tree.
- Differentiate between complete, full, perfect, and balanced binary trees.

## Resources

To successfully complete this project, you are required to read or watch the following resources:

- [Binary Tree](https://en.wikipedia.org/wiki/Binary_tree) (Note: Not to be confused with B-tree.)
- [Data Structure and Algorithms - Tree](https://www.tutorialspoint.com/data_structures_algorithms/tree_data_structure.htm)
- [Tree Traversal](https://en.wikipedia.org/wiki/Tree_traversal)
- [Binary Search Tree](https://en.wikipedia.org/wiki/Binary_search_tree)
- [Data structures: Binary Tree](https://www.geeksforgeeks.org/binary-tree-data-structure/)

## Usage

- All files were created and compiled on Ubuntu 20.04 LTS using gcc 4.8.4 with flags `-Wall -Werror -Wextra -pedantic`.
- Code style adheres to the [Betty](https://github.com/holbertonschool/Betty) style guide.

## Project Structure

The project structure follows this layout:

```
binary_trees/
│
├── README.md
├── binary_trees.h
├── 0-binary_tree_node.c
├── 1-binary_tree_insert_left.c
├── 2-binary_tree_insert_right.c
└── ...
```

## Table of Contents

Files | Description
----- | -----------
0-binary_tree_node.c | C function that creates a binary tree node
1-binary_tree_insert_left.c | C function that inserts a node as the left-child of another node
2-binary_tree_insert_right.c | C function that inserts a node as the right-child of another node
3-binary_tree_delete.c | C function that deletes an entire binary tree
4-binary_tree_is_leaf.c | C function that checks if a node is a leaf
5-binary_tree_is_root.c | C function that checks if a given node is a root
6-binary_tree_preorder.c | C function that goes through a binary tree using pre-order traversal
7-binary_tree_inorder.c | C function that goes through a binary tree using in-order traversal
8-binary_tree_postorder.c | C function that goes through a binary tree using post-order traversal
9-binary_tree_height.c | C function that measures the height of a binary tree
10-binary_tree_depth.c | C function that measures the depth of a node in a binary tree
11-binary_tree_size.c | C function that measures the size of a binary tree
12-binary_tree_leaves.c | C function that counts the leaves in a binary tree
13-binary_tree_nodes.c | C function that counts the nodes with at least 1 child in a binary tree
14-binary_tree_balance.c | C function that measures the balance factor of a binary tree
15-binary_tree_is_full.c | C function that checks if a binary tree is full
16-binary_tree_is_perfect.c | C function that checks if a binary tree is perfect
17-binary_tree_sibling.c | C function that finds the sibling of a node
18-binary_tree_uncle.c | C function that finds the uncle of a node

## Contributing

Contributions to this project are not expected, as it's meant for personal learning and development. However, feel free to fork the repository and use it for your own educational purposes.

## License

This project is for learning purposes only. All content and resources are used under their respective licenses. 
---

**Author** 
Joe-Chege https://github.com/Joe-Chege