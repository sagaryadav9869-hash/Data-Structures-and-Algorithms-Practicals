# 🧠 Data-Structures-and-Algorithms-Practicals

![Python](https://img.shields.io/badge/Language-Python%203.x-blue?style=flat-square&logo=python)
![Java](https://img.shields.io/badge/Language-Java-orange?style=flat-square&logo=openjdk)
![C](https://img.shields.io/badge/Language-C-lightgrey?style=flat-square&logo=c)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

## 📌 Repository Description

A structured repository of **Data Structures and Algorithms (DSA)** practicals, theoretical documentation, asymptotic complexity analyses, and multi-language implementations in **Python**, **Java**, and **C**—covering foundational structures, recursion, greedy strategies, dynamic programming, and self-balancing trees.

> **GitHub About Description:**  
> *Structured Data Structures & Algorithms (DSA) practicals and study notes covering Arrays, Lists, Stacks, Recursion (Tower of Hanoi), Greedy Algorithms, Dynamic Programming, and AVL Trees.*

---

## 🗂️ Repository Structure

```text
Data-Structures-and-Algorithms-Practicals/
├── README.md
├── 1. what is algorithm.docx
├── 2. what is greedy algorithms.docx
├── 3. AVL tree data structure.docx
├── 4. dynamic programming.docx
├── 5. Algorithms Design Techniques.docx
├── 6. what is difference between list and array.docx
└── tower of honoi.docx
```

---

## 📊 Practicals Overview

| # | Practical Topic | Document File | Key Concepts & Implementations | Languages |
| :-: | :--- | :--- | :--- | :--- |
| **1** | **Algorithms, Stacks & Arrays** | `1. what is algorithm.docx` | Sum of $n$ numbers, Stack (`Push`, `Pop`, `Peek`, `IsEmpty`), Time/Space Complexity, 1D & 2D Array operations | Python, C |
| **2** | **Greedy Algorithms** | `2. what is greedy algorithms.docx` | Greedy choice property, optimal substructure, Minimum Coin Change Problem (`coins = [1, 5, 10, 25]`) | Python |
| **3** | **AVL Tree Data Structure** | `3. AVL tree data structure.docx` | Self-balancing BST, Balance Factor ($\{-1, 0, +1\}$), LL/RR/LR/RL rotations, `insert()`, `delete()`, pre-order traversal | Python |
| **4** | **Dynamic Programming (DP)** | `4. dynamic programming.docx` | Top-Down (Memoization) vs. Bottom-Up (Tabulation), Fibonacci sequence, 0/1 Knapsack DP table | Python |
| **5** | **Algorithm Design Techniques** | `5. Algorithms Design Techniques.docx` | Divide & Conquer, Backtracking, Branch & Bound, Bubble Sort, Binary Search, DFS, Top-Down vs. Bottom-Up design | Python |
| **6** | **Lists vs. Arrays** | `6. what is difference between list and array.docx` | Memory allocation, resizing & type safety comparison, Bubble Sort, Binary Search, Singly Linked List, Stack | Python, Java |
| **7** | **Tower of Hanoi (Recursion)** | `tower of honoi.docx` | Recursive disk transfer ($M(n) = 2^n - 1$), PEAS agent analysis, step-by-step execution trace ($n = 3$) | Python |

---

## ⚡ Time & Space Complexity Summary

| Data Structure / Algorithm | Time Complexity (Average / Worst) | Space Complexity | Paradigm / Structure |
| :--- | :---: | :---: | :--- |
| **1D Array Indexed Access** | $O(1)$ | $O(n)$ | Contiguous Linear Structure |
| **Stack (`Push`, `Pop`, `Peek`)** | $O(1)$ | $O(n)$ | LIFO Linear Structure |
| **Linear Search** | $O(n)$ | $O(1)$ | Sequential Search |
| **Binary Search** | $O(\log n)$ | $O(1)$ | Divide & Conquer |
| **Bubble Sort** | $O(n^2)$ | $O(1)$ | Comparison Sorting |
| **AVL Tree (`Search`, `Insert`, `Delete`)** | $O(\log n)$ | $O(n)$ | Self-Balancing BST |
| **Depth-First Search (DFS)** | $O(V + E)$ | $O(V)$ | Graph Traversal |
| **Fibonacci (DP Tabulation)** | $O(n)$ | $O(n)$ | Dynamic Programming |
| **0/1 Knapsack (DP)** | $O(n \times W)$ | $O(n \times W)$ | Dynamic Programming |
| **Tower of Hanoi** | $O(2^n)$ | $O(n)$ | Recursion |

---

## 🛠️ Tools & Technologies Used

| Category | Tools / Technologies |
| :--- | :--- |
| **Programming Languages** | Python 3.x, Java, C |
| **Libraries & Modules** | `numpy`, `array` (Python), `java.util.ArrayList` (Java), `stdio.h` (C) |
| **Core DSA Concepts** | Asymptotic Complexity ($O$-notation), Recursion, Greedy, DP, AVL Trees, Graph Traversal (DFS) |
| **IDEs & Documentation** | Visual Studio Code, Jupyter Notebook, Microsoft Word (`.docx`) |
| **Version Control** | Git & GitHub |

---

## 🚀 How to Use & Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Data-Structures-and-Algorithms-Practicals.git
   cd Data-Structures-and-Algorithms-Practicals
   ```

2. **Explore the practical documents:**
   Open any `.docx` file to view the theoretical notes, pseudocode, dry-run examples, and source code implementations.

3. **Run extracted code snippets:**
   * **Python:** `python script_name.py`
   * **Java:** `javac Main.java && java Main`
   * **C:** `gcc program.c -o program && ./program`
