# Data Structures & Algorithms (DSA) with Python

A complete, self-contained DSA course, from **"what is DSA?"** to **solved interview problems**, written in Python.

Every notebook follows the same structure:

1. **What it is**, with diagrams and analogies
2. **Why it exists and where it's used** in real systems (Google Maps, databases, caches, Git, compilers, mobile money…)
3. **Build it from scratch** in Python
4. **The Pythonic way** using built-ins (`dict`, `deque`, `heapq`, `bisect`…)
5. **Solved LeetCode problems**, each with: idea → code → time & space complexity → `assert` tests
6. **More practice** (LeetCode numbers) and **key takeaways**

> Every notebook has been executed. If a cell runs without an error, all of its tests pass.

---

## Roadmap

### 00 - Introduction
| # | Notebook | You'll learn |
|---|---|---|
| 00.1 | [Introduction to DSA](00-Introduction/00.1-Introduction-to-DSA.ipynb) | What DSA is, why it exists, where it's used, why companies test it, study plan |
| 00.2 | [Big-O & Complexity](00-Introduction/00.2-Big-O-and-Complexity.ipynb) | Time/space complexity, rules, cost of Python built-ins |
| 00.3 | [Python Toolkit for DSA](00-Introduction/00.3-Python-Toolkit-for-DSA.ipynb) | `Counter`, `defaultdict`, `deque`, `heapq`, `bisect`, `sorted(key=…)`, `@cache`, one-liners |

### 01 - Data Structures
| # | Notebook | Real-world use | Solved problems |
|---|---|---|---|
| 01.1 | [Arrays & Strings](01-Data%20Structures/01.1-Arrays-and-Strings.ipynb) | Images, NumPy, spreadsheets | Running Sum, Rotate Array, Subarray Sum = K, Rotate Image, Spiral Matrix… |
| 01.2 | [Hash Tables & Sets](01-Data%20Structures/01.2-Hash-Tables-and-Sets.ipynb) | Caches, DB indexes, Python itself | Design HashMap, Isomorphic Strings, Valid Sudoku… |
| 01.3 | [Linked Lists](01-Data%20Structures/01.3-Linked-Lists.ipynb) | LRU caches, playlists, undo | Palindrome List, Add Two Numbers, **LRU Cache**… |
| 01.4 | [Stacks & Queues](01-Data%20Structures/01.4-Stacks-and-Queues.ipynb) | Call stack, undo/redo, message queues | Queue via Stacks, Eval RPN, Circular Queue, Sliding Window Max… |
| 01.5 | [Trees & BST](01-Data%20Structures/01.5-Trees-and-BST.ipynb) | File systems, HTML DOM, DB B-trees, ML | Traversals, BST insert/delete, Diameter, Serialize Tree… |
| 01.6 | [Heaps & Priority Queues](01-Data%20Structures/01.6-Heaps-and-Priority-Queues.ipynb) | OS scheduling, Top-K trending, Dijkstra | Merge k Lists, **Median of Stream**, Task Scheduler… |
| 01.7 | [Graphs](01-Data%20Structures/01.7-Graphs.ipynb) | Maps, social networks, the Internet | Clone Graph, Pacific Atlantic, Bipartite… |
| 01.8 | [Tries](01-Data%20Structures/01.8-Tries.ipynb) | Autocomplete, spell-check, IP routing | Implement Trie, Add & Search Words, Word Search II |
| 01.9 | [Union-Find](01-Data%20Structures/01.9-Union-Find.ipynb) | Network connectivity, Kruskal's MST | Provinces, Redundant Connection, Accounts Merge |

### 02 - Algorithms
| # | Notebook | Real-world use | Solved problems |
|---|---|---|---|
| 02.1 | [Recursion](02-Algorithms/02.1-Recursion.ipynb) | Folders, parsers, compilers | Pow(x, n), Generate Parentheses, Tower of Hanoi… |
| 02.2 | [Searching & Binary Search](02-Algorithms/02.2-Searching-and-Binary-Search.ipynb) | DB indexes, `git bisect` | First/Last Position, Search 2D Matrix, Ship Packages… |
| 02.3 | [Sorting Algorithms](02-Algorithms/02.3-Sorting-Algorithms.ipynb) | `ORDER BY`, rankings, big-data | Bubble → Merge → Quick → Counting sort, Sort Colors, Inversions… |
| 02.4 | [Graph Algorithms](02-Algorithms/02.4-Graph-Algorithms.ipynb) | GPS routing, package managers, cable networks | BFS, Topological Sort, **Dijkstra**, Bellman-Ford, Kruskal/Prim, Word Ladder… |
| 02.5 | [Greedy](02-Algorithms/02.5-Greedy-Algorithms.ipynb) | Huffman compression, scheduling | Jump Game, Gas Station, Partition Labels… |
| 02.6 | [Backtracking](02-Algorithms/02.6-Backtracking.ipynb) | Sudoku & constraint solvers | Word Search, **N-Queens**, **Sudoku Solver**… |
| 02.7 | [Dynamic Programming](02-Algorithms/02.7-Dynamic-Programming.ipynb) | `git diff`, spell-check, DNA alignment | Decode Ways, Word Break, **Knapsack**, **Edit Distance**… |
| 02.8 | [Bit Manipulation](02-Algorithms/02.8-Bit-Manipulation.ipynb) | File permissions, subnets, crypto | Single Number, Counting Bits, Sum Without `+`… |

### 03 - Interview Patterns
| # | Notebook | Content |
|---|---|---|
| 03.1 | [Most-Asked Problems by Pattern](03-Interview%20Patterns/03.1-Most-Asked-Problems-by-Pattern.ipynb) | 44 classic problems in 12 patterns, a pattern-recognition cheat sheet, the interview routine, and 8 practice problems |

---

## Suggested 8-week plan (1–2 hours/day)

| Week | Study |
|---|---|
| 1 | 00.1 – 00.3, 01.1, 01.2 |
| 2 | 01.3, 01.4, 02.1 |
| 3 | 02.2, 02.3, 01.5 |
| 4 | 01.6, 01.7, 01.8, 01.9 |
| 5 | 02.4, 02.5 |
| 6 | 02.6, 02.7 |
| 7 | 02.8, 03.1 |
| 8 | Re-solve everything on LeetCode from memory, then continue with NeetCode 150 |

## Prerequisites (from the main Python course)

- `3-Data Structures` (lists, tuples, sets, dictionaries)
- `2-Control Flow/Loops.ipynb`
- `4-Functions` (4.1 – 4.3: functions, recursion example, lambda)
- `8-Class And Objects/8.1-oops.ipynb`

## How to study

1. Try every problem **yourself first** (15–30 min) before reading the solution.
2. Remember the **idea**, not the code.
3. Re-solve on LeetCode from memory after 2–3 days.
4. Always say the **time and space complexity** out loud.
