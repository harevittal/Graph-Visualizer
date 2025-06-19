# 🔗 Graph Visualizer (Text-based)

A simple, interactive **Command Line Interface (CLI)** tool to create, display, and explore graphs using classic algorithms like **BFS**, **DFS**, and **Dijkstra’s shortest path algorithm**. Designed for learners and developers who want to understand and practice graph algorithms in a hands-on way — without any GUI.

---

##  Features

##  User Interface Menu

```
1. Add Edge
2. Display Adjacency List
3. BFS Traversal
4. DFS Traversal
5. Dijkstra's Shortest Path
0. Exit
```

###  1. Graph Representation
- Uses an **adjacency list** for efficient storage.
- Implemented as:
  ```cpp
  unordered_map<int, vector<pair<int, int>>> adj;
  ```
  Each node maps to a list of `(neighbor, weight)` pairs.

---

###  2. Add Edges
- Supports **undirected** and **weighted** edges.
- Input format: `Source Destination Weight`
- Automatically adds both directions.

---

###  3. Display Adjacency List
- Shows the internal structure of the graph.
- Example output:
  ```
  1 -> (2, weight=2) (3, weight=5)
  2 -> (1, weight=2) (3, weight=1) (4, weight=2)
  ```

---

###  4. BFS Traversal
- Breadth-First Search using a **queue**.
- Visits nodes level-by-level.
- Input: Starting node
- Output: Order of node visits.

---

###  5. DFS Traversal
- Depth-First Search using **recursion**.
- Visits as deep as possible before backtracking.
- Input: Starting node
- Output: Order of node visits.

---

###  6. Dijkstra’s Shortest Path Algorithm
- Computes **minimum distances** from a start node to all others.
- Uses a **priority queue (min-heap)** and greedy strategy.
- Works on graphs with **positive edge weights** only.

---

## Concepts Used

- **Language:** C++
- **STL Containers:** `unordered_map`, `vector`, `queue`, `priority_queue`, `set`
- **Algorithms:**
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
  - Dijkstra’s Algorithm

---




