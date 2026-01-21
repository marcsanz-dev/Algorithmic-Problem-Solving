# 🧠 Algorithmic Problem Solving Collection

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![CV](https://img.shields.io/badge/Computer_Vision-OpenCV-green?style=for-the-badge)

A comprehensive collection of advanced algorithmic problems solved using Python. This repository explores different paradigms (**Greedy, Dynamic Programming, Backtracking, and Graph Theory**) to solve complex optimization and logic challenges.

## 📂 Project Modules

### 1. State Space Search (Graphs)
* **File:** `01_Graph_Exploration.ipynb`
* **Problem:** **The Knapsack Problem** modeled as a graph.
* **Approach:** Instead of the traditional tabular DP approach, this solution models the problem as a **State Space Search**.
    * Implements **BFS (Breadth-First Search)** to explore possible combinations.
    * Uses **Dijkstra's Algorithm** to find the optimal path (maximum value/weight ratio) in the graph of states.

### 2. Greedy Optimization & Encoding
* **File:** `02_Greedy_Optimization.ipynb`
* **Problems Solved:**
    * **Refueling Problem:** Optimization of stops and cost for a vehicle traveling from A to B (minimizing local costs).
    * **Alphabet Encoding:** Constructing an efficient encoding system for an alphabet using graph theory (Prefix Codes/Huffman-style logic).

### 3. Computer Vision & Dynamic Programming (Seam Carving)
* **File:** `03_Dynamic_Programming.ipynb`
* **Core Concept:** **Seam Carving** (Content-Aware Image Resizing).
* **Functionality:**
    * **Vertical Resizing:** Reduces image width by iteratively removing the "lowest energy" vertical seams (paths of least importance), preserving main subjects.
    * **Object Removal:** Removes specific marked patches from an image by forcing the algorithm to route seams through the target area.
* **Test Cases:** Processed complex images like `fireball` and `beach`.

### 4. Constraint Satisfaction (Backtracking)
* **File:** `04_Backtracking_Skyscrapers.ipynb`
* **Problem:** **The Skyscrapers Puzzle** (N*N grid logic game).
* **Highlights:**
    * Implements a highly optimized recursive solver.
    * Uses **Constraint Propagation** and lookup tables (base cases) to prune the search tree.
    * Drastically reduces execution time compared to brute force approaches.

---

## 🚀 Key Skills Demonstrated
* **Algorithm Selection:** Choosing the right paradigm (Greedy vs. DP) based on problem substructure.
* **Optimization:** Reducing time complexity in NP-hard problems using pruning and heuristics.
* **Modeling:** transforming abstract constraints (like the Knapsack capacity) into graph traversals.
* **Image Processing:** Manipulating pixel arrays based on energy functions (gradients).
