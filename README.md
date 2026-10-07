# 🚀 Java DSA Practice

<div align="center">

# 🧠 Data Structures & Algorithms

### A structured Java repository for learning, practicing, and mastering Data Structures & Algorithms.

<p>
<strong>Java • DSA • Problem Solving • Algorithms • Interview Preparation</strong>
</p>

</div>

---

## 📖 About This Repository

Welcome to my **Java Data Structures & Algorithms Practice Repository**.

This repository contains my journey of learning and implementing **DSA concepts using Java**, starting from basic programming concepts and gradually moving toward advanced problem-solving techniques.

The main objective is to improve:

- 🧠 Problem-solving skills
- 💻 Java programming skills
- ⚡ Algorithmic thinking
- 📊 Time & Space Complexity analysis
- 🎯 Technical interview preparation
- 🚀 Competitive programming skills

Each topic contains practical Java implementations and problem-solving examples.

---

## 🛠️ Technology

<div align="center">

| Technology | Version / Usage |
|---|---|
| ☕ Java | JDK 17+ |
| 🌱 Spring Boot | Used where required |
| 📦 Java Collections | Core DSA Practice |
| 🔧 Git | Version Control |
| 🐙 GitHub | Repository & Progress Tracking |

</div>

---

# 📚 DSA Topics

<table>
<tr>

<td valign="top" width="33%">

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

</td>

<td valign="top" width="33%">

### 🔹 Strings

- String Manipulation
- String Reversal
- Palindrome
- Anagram
- Character Frequency
- Duplicate Characters
- Substrings
- String Compression

</td>

<td valign="top" width="33%">

### 🔹 Searching

- Linear Search
- Binary Search
- First & Last Occurrence
- Search in Rotated Array
- Search on Answer

</td>

</tr>

<tr>

<td valign="top" width="33%">

### 🔹 Sorting

- Bubble Sort
- Selection Sort
- Insertion Sort
- Merge Sort
- Quick Sort
- Heap Sort
- Counting Sort

</td>

<td valign="top" width="33%">

### 🔹 Recursion

- Basic Recursion
- Factorial
- Fibonacci
- Sum Problems
- String Problems
- Subsets
- Subsequences
- Backtracking

</td>

<td valign="top" width="33%">

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

</td>

</tr>

<tr>

<td valign="top" width="33%">

### 🔹 Stack

- Stack Implementation
- Balanced Parentheses
- Next Greater Element
- Previous Greater Element
- Min Stack
- Expression Evaluation

</td>

<td valign="top" width="33%">

### 🔹 Queue

- Queue
- Circular Queue
- Deque
- Priority Queue
- BFS

</td>

<td valign="top" width="33%">

### 🔹 Hashing

- HashMap
- HashSet
- Frequency Counting
- Duplicate Detection
- Two Sum
- Subarray Sum

</td>

</tr>

<tr>

<td valign="top" width="33%">

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

</td>

<td valign="top" width="33%">

### 🔹 Heap

- Min Heap
- Max Heap
- Priority Queue
- Heap Sort
- Kth Largest
- Kth Smallest
- Top K Problems

</td>

<td valign="top" width="33%">

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

</td>

</tr>

<tr>

<td valign="top" width="33%">

### 🔹 Greedy

- Activity Selection
- Fractional Knapsack
- Job Sequencing
- Minimum Coins
- Interval Problems
- Jump Game

</td>

<td valign="top" width="33%">

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

</td>

<td valign="top" width="33%">

### 🔹 Backtracking

- Subsets
- Permutations
- Combination Sum
- N-Queens
- Sudoku
- Rat in a Maze
- Word Search

</td>

</tr>
</table>

---

# 📂 Repository Structure

```text
java-dsa-practice/
│
├── arrays/
│   ├── OneDimensionalArray1.java
│   ├── OneDimensionalArray2.java
│   ├── OneDimensionalArray3.java
│   └── ...
│
├── strings/
│
├── searching/
│
├── sorting/
│
├── recursion/
│
├── linkedlist/
│
├── stack/
│
├── queue/
│
├── hashing/
│
├── trees/
│
├── heap/
│
├── graph/
│
├── greedy/
│
├── dynamicprogramming/
│
└── backtracking/
```

---

# 🧩 Problem-Solving Approach

For every problem, the approach is:

```text
                Problem
                   │
                   ▼
          Understand the Problem
                   │
                   ▼
          Identify Constraints
                   │
                   ▼
        Find Brute Force Solution
                   │
                   ▼
          Analyze Complexity
                   │
                   ▼
            Optimize Solution
                   │
                   ▼
           Implement in Java
                   │
                   ▼
             Test Edge Cases
                   │
                   ▼
       Analyze Time & Space Complexity
```

---

# ⏱️ Time Complexity

Understanding complexity is one of the most important parts of DSA.

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

# 💻 Java Coding Example

### Two Sum

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

### Complexity

```text
Time Complexity  : O(n²)
Space Complexity : O(1)
```

---

# 🗺️ DSA Learning Roadmap

```text
Java Fundamentals
        │
        ▼
     Arrays
        │
        ▼
     Strings
        │
        ▼
   Collections
        │
        ▼
    Searching
        │
        ▼
     Sorting
        │
        ▼
    Recursion
        │
        ▼
   Linked List
        │
        ▼
 Stack & Queue
        │
        ▼
     Hashing
        │
        ▼
      Trees
        │
        ▼
      Heap
        │
        ▼
     Graphs
        │
        ▼
     Greedy
        │
        ▼
  Backtracking
        │
        ▼
Dynamic Programming
        │
        ▼
Advanced Problem Solving
```

---

# 🎯 Goals

- [x] Start Java DSA practice
- [x] Practice basic Arrays
- [ ] Complete Arrays
- [ ] Complete Strings
- [ ] Master Java Collections
- [ ] Master Searching
- [ ] Master Sorting
- [ ] Master Recursion
- [ ] Master Linked Lists
- [ ] Master Stack & Queue
- [ ] Master Hashing
- [ ] Master Trees
- [ ] Master Heap
- [ ] Master Graphs
- [ ] Master Greedy Algorithms
- [ ] Master Backtracking
- [ ] Master Dynamic Programming
- [ ] Solve 500+ DSA problems
- [ ] Improve problem-solving speed
- [ ] Prepare for technical interviews

---

# 🏆 Practice Platforms

Problems and concepts are practiced using various coding platforms:

- [LeetCode](https://leetcode.com/)
- [GeeksforGeeks](https://www.geeksforgeeks.org/)
- [HackerRank](https://www.hackerrank.com/)
- [CodeChef](https://www.codechef.com/)
- [Codeforces](https://codeforces.com/)

---

# 📈 Progress Tracking

| Category | Status |
|---|---|
| Arrays | 🟢 In Progress |
| Strings | 🟡 Learning |
| Searching | 🟡 Learning |
| Sorting | 🟡 Learning |
| Recursion | 🟡 Learning |
| Linked List | 🟡 Learning |
| Stack | 🟡 Learning |
| Queue | 🟡 Learning |
| Hashing | 🟡 Learning |
| Trees | 🟡 Learning |
| Heap | 🟡 Learning |
| Graph | 🟡 Learning |
| Greedy | 🟡 Learning |
| Dynamic Programming | 🟡 Learning |
| Backtracking | 🟡 Learning |

---

# 🧠 Core Principles

> **Understand the logic, don't just memorize the solution.**

For every problem:

```text
Understand
    ↓
Think
    ↓
Solve
    ↓
Optimize
    ↓
Implement
    ↓
Analyze
    ↓
Repeat
```

---

# 🚀 Why This Repository?

This repository is more than a collection of solutions.

It is a structured learning journey focused on:

- Building strong DSA fundamentals
- Understanding algorithms deeply
- Writing clean Java code
- Improving coding efficiency
- Learning optimization techniques
- Preparing for real-world technical interviews

---

# 👨‍💻 Author

<div align="center">

## Debasish Mohanta

### Java Backend Developer

**Java • Spring Boot • Microservices • REST APIs • SQL • DSA**

</div>

---

<div align="center">

### ⭐ If this repository helps you, consider giving it a star!

### 💻 Keep Coding • 🧠 Keep Learning • 🚀 Keep Growing

</div>
