# 🚀 Java DSA Practice

<div align="center">

<h1>🧠 Data Structures & Algorithms</h1>

<p>
A structured collection of Data Structures, Algorithms, problem-solving techniques,
and Java implementations for learning, practice, and interview preparation.
</p>

</div>

---

## 📖 About

This repository contains my **Data Structures and Algorithms (DSA) practice using Java**.

The purpose of this repository is to build strong problem-solving skills by implementing DSA concepts from the basics to advanced topics.

Each problem focuses on understanding:

- The problem statement
- Logical approach
- Java implementation
- Time complexity
- Space complexity
- Possible optimizations

---

## 🛠️ Tech Stack

- ☕ Java
- 💻 JDK 17+
- 🌱 Spring Boot (where required for practice)
- 📦 Java Collections Framework
- 🔧 Git & GitHub

---

## 📚 Topics Covered

### 🔹 Arrays

- One Dimensional Arrays
- Two Dimensional Arrays
- Array Traversal
- Searching
- Insertion & Deletion
- Reverse Array
- Duplicate Elements
- Frequency Counting
- Prefix Sum
- Two Pointer
- Sliding Window
- Subarrays

### 🔹 Strings

- String Manipulation
- String Reversal
- Palindrome
- Anagram
- Character Frequency
- Duplicate Characters
- Substrings
- String Compression

### 🔹 Searching

- Linear Search
- Binary Search
- First & Last Occurrence
- Search in Rotated Array
- Search on Answer

### 🔹 Sorting

- Bubble Sort
- Selection Sort
- Insertion Sort
- Merge Sort
- Quick Sort
- Heap Sort
- Counting Sort

### 🔹 Recursion

- Basic Recursion
- Factorial
- Fibonacci
- Sum Problems
- String Problems
- Subsets
- Subsequences
- Backtracking

### 🔹 Linked List

- Singly Linked List
- Doubly Linked List
- Circular Linked List
- Insertion
- Deletion
- Reverse Linked List
- Middle Node
- Cycle Detection
- Merge Linked Lists

### 🔹 Stack

- Stack Implementation
- Balanced Parentheses
- Next Greater Element
- Previous Greater Element
- Min Stack
- Expression Evaluation

### 🔹 Queue

- Queue
- Circular Queue
- Deque
- Priority Queue
- BFS

### 🔹 Hashing

- HashMap
- HashSet
- Frequency Counting
- Duplicate Detection
- Two Sum
- Subarray Sum

### 🔹 Trees

- Binary Tree
- Binary Search Tree
- Preorder
- Inorder
- Postorder
- Level Order
- Height
- Diameter
- Lowest Common Ancestor

### 🔹 Heap

- Min Heap
- Max Heap
- Priority Queue
- Heap Sort
- Kth Largest
- Kth Smallest
- Top K Problems

### 🔹 Graph

- Graph Representation
- Adjacency Matrix
- Adjacency List
- BFS
- DFS
- Cycle Detection
- Connected Components
- Shortest Path
- Dijkstra
- Topological Sort
- Minimum Spanning Tree

### 🔹 Greedy

- Activity Selection
- Fractional Knapsack
- Job Sequencing
- Minimum Coins
- Interval Problems
- Jump Game

### 🔹 Dynamic Programming

- Memoization
- Tabulation
- Fibonacci
- Climbing Stairs
- 0/1 Knapsack
- Coin Change
- Longest Common Subsequence
- Longest Increasing Subsequence
- House Robber

### 🔹 Backtracking

- Subsets
- Permutations
- Combination Sum
- N-Queens
- Sudoku
- Rat in a Maze
- Word Search

---

## 📂 Repository Structure

```text
java-dsa-practice/
│
├── arrays/
├── strings/
├── searching/
├── sorting/
├── recursion/
├── linkedlist/
├── stack/
├── queue/
├── hashing/
├── tree/
├── heap/
├── graph/
├── greedy/
├── dynamicprogramming/
└── backtracking/
```

---

## 🧩 Problem-Solving Approach

For every problem, I follow:

```text
Understand Problem
       ↓
Identify Constraints
       ↓
Find Brute Force Approach
       ↓
Analyze Complexity
       ↓
Optimize Solution
       ↓
Implement in Java
       ↓
Test Edge Cases
       ↓
Analyze Time & Space Complexity
```

---

## ⏱️ Time Complexity

| Complexity | Example |
|---|---|
| `O(1)` | Array Access |
| `O(log n)` | Binary Search |
| `O(n)` | Linear Search |
| `O(n log n)` | Merge Sort |
| `O(n²)` | Bubble Sort |
| `O(2ⁿ)` | Subsets |
| `O(n!)` | Permutations |

---

## 🎯 Goals

- [x] Learn Java fundamentals
- [x] Practice Arrays
- [ ] Master Java Collections
- [ ] Master Searching & Sorting
- [ ] Master Linked Lists
- [ ] Master Stack & Queue
- [ ] Master Trees
- [ ] Master Graphs
- [ ] Learn Dynamic Programming
- [ ] Practice Backtracking
- [ ] Solve 500+ DSA problems
- [ ] Improve problem-solving speed
- [ ] Prepare for technical interviews

---

## 💻 Example

```java
public class TwoSum {

    public static int[] twoSum(int[] nums, int target) {

        for (int i = 0; i < nums.length; i++) {

            for (int j = i + 1; j < nums.length; j++) {

                if (nums[i] + nums[j] == target) {
                    return new int[]{i, j};
                }
            }
        }

        return new int[]{};
    }

    public static void main(String[] args) {

        int[] nums = {2, 7, 11, 15};
        int target = 9;

        int[] result = twoSum(nums, target);

        System.out.println(result[0] + " " + result[1]);
    }
}
```

**Time Complexity:** `O(n²)`

**Space Complexity:** `O(1)`

---

## 🏆 Practice Platforms

Problems are practiced from:

- [LeetCode](https://leetcode.com/)
- [GeeksforGeeks](https://www.geeksforgeeks.org/)
- [HackerRank](https://www.hackerrank.com/)
- [CodeChef](https://www.codechef.com/)
- [Codeforces](https://codeforces.com/)

---

## 📈 Learning Roadmap

```text
Java Basics
     ↓
Arrays
     ↓
Strings
     ↓
Collections
     ↓
Searching
     ↓
Sorting
     ↓
Recursion
     ↓
Linked List
     ↓
Stack & Queue
     ↓
Hashing
     ↓
Trees
     ↓
Heap
     ↓
Graphs
     ↓
Greedy
     ↓
Backtracking
     ↓
Dynamic Programming
     ↓
Advanced Problem Solving
```

---

## 👨‍💻 Author

**Debasish Mohanta**

Java Backend Developer

```text
Java • Spring Boot • Microservices • REST APIs • SQL • DSA
```

---

<div align="center">

### ⭐ Keep Learning • Keep Coding • Keep Solving 🚀

</div>
