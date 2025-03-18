# Assignment 4: Sorted Data Structures

This repository contains the implementation of **SortedLinkedList**, **SortedArray**, and performance tests for various data structures as part of Assignment 4 for the **Data Structures and Algorithms** course.

---

## Table of Contents
1. [Overview](#overview)
2. [Requirements](#requirements)
3. [Implementation](#implementation)
4. [How to Run](#how-to-run)
5. [Performance Results](#performance-results)
6. [Answers to Questions](#answers-to-questions)
7. [Files](#files)
8. [References](#references)

---

## Overview
The goal of this assignment is to implement and compare the performance of three data structures:
1. **SortedLinkedList**: A linked list that maintains elements in sorted order.
2. **SortedArray**: An array-based list that maintains elements in sorted order.
3. **ArrayList**: A standard Java `ArrayList` that sorts elements after each insertion.

The performance of these data structures is tested using a dataset of names from the file `bnames.txt`.

---

## Requirements
The assignment requires the following:
1. Implement the `add`, `get`, and `remove` methods for `SortedLinkedList` and `SortedArray`.
2. Add a second linked list in `runPartA` to demonstrate functionality with a different data type (e.g., `Integer`).
3. Implement performance tests for:
   - **ArrayList** with built-in sort.
   - **Primitive Array** with insertion sort (`iSort`).
   - **SortedLinkedList**.
   - **SortedArray**.
4. Include a performance comparison and answers to the provided questions.

---

## Implementation
### Key Features
- **SortedLinkedList**:
  - Maintains elements in sorted order during insertion.
  - Supports `add`, `get`, and `remove` operations.
- **SortedArray**:
  - Maintains elements in sorted order during insertion.
  - Uses an `ArrayList` internally for dynamic resizing.
- **Performance Tests**:
  - Measure the time taken to build each data structure.
  - Validate the sorted order using the `ckSumSorted` method.

---

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/assignment4.git
   cd assignment4
