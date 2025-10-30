Okay, here is the same README **without hashtags, icons, headings, or decorative formatting**.
Just clean, plain text:

---

CS2012 – Object-Oriented Programming
Assignment #2 – Fall 2025

This repository contains my solutions for OOP Assignment #2. The work focuses on implementing recursion, lists, stacks, and queues in C++. All programs are written with proper structure and clear logic.

---

Question 1 – Recursion

(a) ChangeLocation
Function: void ChangeLocation(char* arr, int b1, int b2);
This function uses recursion to swap the characters located at the two specified indices in a character array.

Example:
Input: {C, O, M, P, U, T, E, R}, b1 = 3, b2 = 7
Output: {C, O, E, P, U, T, M, R}

(b) PrintPattern
Function: void PrintPattern(int &n);
This function prints a nested pattern using recursion, showing how values change during repeated calls.

---

Question 2 – Singly Linked List (NASA Remote Feature Tracking System)

This part involves managing geographic feature information using a singly linked list.

Classes involved:

* Feature (base class, contains name and a pure virtual function analyze())
* LandFeature and WaterFeature (derived classes that provide their own versions of analyze())
* SinglyLinkedList (supports insertion, deletion, traversal, and reversing)

Concepts demonstrated include polymorphism, inheritance, and dynamic memory handling.

---

Question 3 – Doubly Linked List (Library System)

A doubly linked list is used to store and manage book records.
Each node contains: BookID, Title, and Author.

Operations supported:

* Add a book at the beginning, at the end, or at a specific index
* Delete a book using its BookID
* Display the list forward (using the head pointer)
* Display the list backward (using the tail pointer)

---

Question 4 – Queue (Movie Ticket Booking System)

This part simulates a movie ticket booking process using a queue structure.

Each customer record stores:
CustomerID, CustomerName, and TicketsRequested.

Functions included:

* enqueue(): Add customer to the end of the queue
* dequeue(): Remove customer from the front of the queue (FIFO)
* display(): Show the current queue contents

Dynamic memory is managed manually.

---

Question 5 – Stack Implementations and Comparison

Two stack versions are implemented:

1. Array-based stack
2. Linked list-based stack

Both are used to convert previously recursive solutions into iterative ones.

Comparison Summary:

* Both allow push and pop in O(1) time.
* Array-based stack has better cache performance but limited or resizable capacity.
* Linked list-based stack grows dynamically but requires extra memory for pointers.

---

Key Concepts Demonstrated:

* Recursion and conversion to iteration
* Singly and doubly linked lists
* Stack and queue implementation
* Inheritance and polymorphism
* Dynamic memory allocation
* Basic algorithm efficiency analysis

---

