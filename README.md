# AlgoMuseum

Welcome to **AlgoMuseum** — a virtual museum where algorithms are displayed as exhibits.

Instead of simply storing code solutions, AlgoMuseum presents every algorithm as a historical artifact with its own gallery, explanation, complexity analysis, walkthrough, and implementation.

Every exhibit answers:

* What problem does this algorithm solve?
* How does it work?
* When should it be used?
* What are its strengths and weaknesses?
* What is its time and space complexity?

---

## Museum Map

```text
algomuseum/
│
├── README.md
│
├── halls/
│   │
│   ├── hall_of_sorting/
│   │   └── merge_sort/
│   │       ├── exhibit.md
│   │       ├── implementation.py
│   │       ├── complexity.md
│   │       └── walkthrough.md
│   │
│   ├── hall_of_backtracking/
│   │   └── rat_in_maze/
│   │       ├── exhibit.md
│   │       ├── implementation.py
│   │       ├── complexity.md
│   │       └── walkthrough.md
│   │
│   ├── hall_of_recursion/
│   │
│   ├── hall_of_graphs/
│   │
│   ├── hall_of_dynamic_programming/
│   │
│   └── hall_of_greedy_algorithms/
│
├── visitor_guide/
│   ├── algorithm_patterns.md
│   ├── interview_notes.md
│   └── complexity_cheatsheet.md
│
└── assets/
    ├── images/
    └── diagrams/
```

---

## Current Exhibits

### Exhibit 001: Merge Sort

Location: Hall of Sorting

#### Description

Merge Sort is a Divide and Conquer algorithm that repeatedly divides an array into smaller halves, sorts them independently, and merges them back together.

#### Highlights

* Stable sorting algorithm
* Guaranteed O(N log N)
* Widely used in real-world systems

#### Complexity

| Metric | Value      |
| ------ | ---------- |
| Time   | O(N log N) |
| Space  | O(N)       |

---

### Exhibit 002: Rat in a Maze

Location: Hall of Backtracking

#### Description

Rat in a Maze demonstrates the power of Backtracking by exploring every valid path from source to destination while avoiding invalid routes and cycles.

#### Highlights

* Classic Backtracking problem
* Uses DFS traversal
* Generates all valid paths

#### Complexity

| Metric | Value     |
| ------ | --------- |
| Time   | O(4^(N²)) |
| Space  | O(N²)     |

---

## Future Exhibits

### Hall of Sorting

* Merge Sort
* Quick Sort
* Heap Sort
* Counting Sort
* Radix Sort

### Hall of Backtracking

* Rat in a Maze
* N Queens
* Sudoku Solver
* Word Search
* Knight Tour

### Hall of Graphs

* BFS
* DFS
* Dijkstra
* Bellman Ford
* Floyd Warshall

### Hall of Dynamic Programming

* Knapsack
* Longest Common Subsequence
* Longest Increasing Subsequence
* Matrix Chain Multiplication

### Hall of Greedy Algorithms

* Activity Selection
* Huffman Coding
* Fractional Knapsack

---

## Mission

AlgoMuseum transforms algorithm learning into an exploration experience.

Every algorithm is treated as an exhibit rather than just a code file, making learning more engaging, structured, and memorable.

---

## Additional Repository Structure

```text
algomuseum/
│
├── curator_notes/
│   ├── why_merge_sort.md
│   └── why_backtracking.md
│
├── featured_exhibits/
│   └── exhibit_of_the_month.md
│
└── visitor_challenges/
    ├── beginner.md
    ├── intermediate.md
    └── expert.md
```

AlgoMuseum is designed to grow into a complete collection of algorithmic patterns, interview problems, and educational resources organized as museum exhibits.
