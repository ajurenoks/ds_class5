# Graph Traversal Algorithms in Python

This repository is dedicated to showcasing implementations of various graph traversal algorithms in Python, specifically focusing on Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms. These algorithms are foundational for exploring and navigating through graph data structures and find extensive applications in areas such as AI, web crawling, network analysis, and more.

## Overview of Algorithms

### Breadth-First Search (BFS)

BFS is an algorithm for traversing or searching tree or graph data structures. It starts at a chosen node (often the root in the case of trees) and explores all of the neighbor nodes at the present depth prior to moving on to the nodes at the next depth level. It employs a queue to keep track of the nodes that are to be explored.

**File:** `solution-bfs.py`  
This Python script demonstrates the BFS algorithm for navigating through a graph represented as an adjacency list.

### Depth-First Search (DFS)

DFS is an algorithm for traversing or searching tree or graph data structures by starting at the root (choosing some arbitrary node as the root in the case of a graph) and exploring as far as possible along each branch before backtracking. DFS can manifest in three types:

- **In-Order Traversal** (applicable for binary trees): Visits the left child, then the node, and finally the right child.
- **Pre-Order Traversal**: Visits the node before its children.
- **Post-Order Traversal**: Visits the node after its children.

**Files:**  
- `solution-dfs_in_order.py`: Implements DFS in-order traversal for binary trees.
- `solution-dfs_pre_order.py`: Implements DFS pre-order traversal for trees or graphs.
- `solution-dfs_post_order.py`: Implements DFS post-order traversal for trees or graphs.

## Getting Started

These Python scripts are designed to be straightforward to run on any system with Python installed. To execute any of the scripts, simply navigate to the directory containing the script and run:

```bash
python <script_name>.py
