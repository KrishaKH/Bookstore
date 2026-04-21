# Bookstore System and Data Structures Implementation

## Overview
This project is a Python-based application that combines a bookstore management system with an expression calculator to demonstrate the practical implementation of core data structures and algorithms.

All data structures are built from scratch without relying on Python’s built-in equivalents, emphasizing a deep understanding of underlying logic, performance, and design trade-offs.

---

## Key Highlights
- Implemented multiple data structures from scratch, including trees, graphs, heaps, and hash tables  
- Designed a functional bookstore system with search, sorting, and cart management  
- Built an expression calculator using stack-based parsing and evaluation  
- Applied object-oriented programming and modular design principles  
- Demonstrates strong understanding of algorithmic problem solving  

---

## Features

### Bookstore System
- Load and manage book data  
- Search and sort books efficiently  
- Add and manage items in a shopping cart  
- Utilize multiple data structures for optimized operations  

### Expression Calculator
- Evaluate mathematical expressions  
- Support for variables and assignments  
- Stack-based expression parsing  

---

## Data Structures Implemented

All implementations are written from scratch for educational and performance understanding.

### Linear Structures
- Stack (Array-based, Linked List)
- Queue (Array-based, Linked List, Random Queue, Max Queue)
- List (ArrayList, Doubly Linked List)
- Deque

### Tree Structures
- Binary Search Tree (BST)
- Red-Black Tree (Self-balancing tree)

### Hashing
- Chained Hash Table

### Priority Structures
- Binary Heap (Priority Queue)

### Graphs
- Adjacency List
- Adjacency Matrix

---

## Algorithms
- Custom sorting algorithms  
- Expression parsing using stacks  
- Tree-based and graph-based data organization  

---

## System Architecture

```
Stack
 ├── ArrayStack
 └── SLLStack     

Queue   
 ├── ArrayQueue
 │    ├── RandomQueue
 │    └── MaxQueue
 ├── SLLQueue
 └── BinaryHeap

List
 ├── ArrayList
 │    └── ArrayDeque
 └── DLList
      └── DLLDeque

Set
 ├── ChainedHashTable
 ├── BinarySearchTree
 └── RedBlackTree

Graph
 ├── AdjacencyMatrix
 └── AdjacencyList
```

---

## Project Structure

### Core Application
- **main.py** – Entry point and menu navigation  
- **BookStore.py** – Bookstore logic and operations  
- **Calculator.py** – Expression evaluation engine  

### Data Models
- **Book.py** – Book data representation  
- **SortableBook.py** – Book comparison logic  

### Data Structures
- Stack, Queue, List, Deque implementations  
- Hash tables, trees, heaps, and graphs  

### Algorithms
- **algorithms.py** – Sorting implementations  

---

## How to Run

Ensure Python 3.8 or higher is installed.

```bash
python3 main.py
```

---

## Example Usage

```
1 Calculator
2 Bookstore System
0 Exit
```

- Select option 1 to evaluate expressions  
- Select option 2 to interact with the bookstore  
- Select option 0 to exit  

---

## Installation

```bash
pip install numpy
```

Recommended IDE: PyCharm  
https://www.jetbrains.com/pycharm/

---

## Technical Skills Demonstrated

- Data Structures and Algorithms  
- Object-Oriented Programming (OOP)  
- Problem Solving and System Design  
- Modular Code Architecture  
- Algorithm Optimization  

---

## Learning Outcomes

- Developed a deep understanding of how data structures work internally  
- Learned how to apply algorithms in real-world systems  
- Gained experience designing scalable and maintainable code  
- Strengthened debugging and problem-solving skills  

---

## Future Improvements
- Add graphical user interface (GUI)  
- Integrate database for persistent storage  
- Improve search performance with advanced indexing  
- Add unit testing for all data structures  

---

## Author
Krisha
