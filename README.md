# C Data Structures and Algorithms

## Overview
This project is a collection of implementations for various fundamental data structures and algorithms in C. Each file is a standalone program that demonstrates key concepts such as pointers, linked lists (singly, doubly, and circular), stacks, queues, binary trees, graphs, and expression conversion/evaluation (infix to postfix). The code is written with detailed comments to serve as an educational resource for understanding these concepts in C.

## Project Files
- **01-Pointer.c**  
  Demonstrates basic pointer usage, pointer arithmetic, double pointers, and function pointers.

- **02-singleLinkedList.c**  
  Implements a singly linked list with functions for:
  - Insertion at the beginning, at the end, and after a given index.
  - Deletion from the beginning, end, or a specific index.
  - Reversing the linked list.
  - Printing the list.

- **03-doubleLinkedList.c**  
  Provides an implementation of a doubly linked list with:
  - Insertion at the beginning, end, and after a specified index.
  - Deletion from the beginning, end, and at a given index.
  - Reversing the doubly linked list.
  - Printing the list.

- **04-circularLinkedList.c**  
  Implements a circular linked list featuring:
  - Insertion at the beginning, at the end, and after a specific target value.
  - Deletion of nodes (including special handling for the head node).
  - Searching for a node.
  - Counting nodes.
  - Displaying the list.

- **05-Stack.c**  
  Demonstrates a stack implementation using an array, including:
  - Push, pop, and peek operations.
  - Checking if the stack is empty or full.
  - Determining the size of the stack.
  - Printing the stack elements.

- **06-infixPosfix.c**  
  Converts an infix expression to a postfix expression using the Shunting-yard algorithm and evaluates the resulting postfix expression. This file includes:
  - A character stack for operators.
  - An integer stack for operands.
  - Functions for operator precedence and conversion.
  - Postfix evaluation logic.

- **07-Queue.c**  
  Implements a queue using an array with functionalities to:
  - Enqueue and dequeue elements.
  - Retrieve the front element without removing it.
  - Display the queue and check its size.

- **08-binaryTree.c**  
  Implements a binary search tree (BST) with operations such as:
  - Insertion and searching.
  - Inorder, preorder, and postorder traversals.
  - Deletion of nodes.
  - Computing the height of the tree.

- **09-Graph.c**  
  Implements an undirected graph using an adjacency matrix, featuring:
  - Adding and removing edges.
  - Depth-first search (DFS) and breadth-first search (BFS) traversals.
  - Printing the adjacency matrix to visualize graph connections.

## How to Compile and Run
Each file is a standalone C program. To compile a specific file, use a C compiler such as GCC. For example, to compile and run the pointer demonstration:

```bash
gcc 01-Pointer.c -o pointer_demo
./pointer_demo
