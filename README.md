# Data Structure Visualizer & Debugger

A free, browser-based tool that runs your own Python data structure code with a real
Python interpreter (via [Pyodide](https://pyodide.org)) and visualizes execution line
by line — the structure redrawn at every step, current line highlighted, and the live
traversal path traced across it.

Auto-detects, from a plain variable in your code, and draws:

- **Binary search trees** (`left`/`right`) and **n-ary trees** (`children` list)
- **Linked lists**, singly or doubly (`next`/`prev`), cycles included
- **Graphs** — node objects with a `neighbors`/`adj` list, or a plain adjacency dict
  like `{'A': ['B', 'C']}`
- **Heaps / arrays** — a plain list of numbers, with a toggle to also view it as the
  implicit binary tree a heap represents
- **Stacks and queues** — a list or `collections.deque` named accordingly, drawn as a
  vertical stack with a "top" marker or a horizontal queue with front/rear labels

