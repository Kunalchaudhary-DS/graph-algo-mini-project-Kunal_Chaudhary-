# Graph Algorithms Assignment

This project demonstrates the implementation and analysis of fundamental graph algorithms used in real-world applications such as network routing, task scheduling, and path finding.

---

## Algorithms Implemented

- **Graph Representation**
  - Adjacency List
  - (Optional) Adjacency Matrix

- **Graph Traversal**
  - Breadth First Search (BFS)
  - Depth First Search (DFS)

- **Topological Sorting**
  - Task scheduling using DAG

- **Shortest Path Algorithms**
  - Dijkstra’s Algorithm
  - Bellman-Ford Algorithm

- **Minimum Spanning Tree**
  - Prim’s Algorithm / Kruskal’s Algorithm

---

## Performance Analysis

The project includes comparison of algorithm performance using:

- BFS vs DFS  
- Dijkstra vs Bellman-Ford  

Execution time is measured and visualized using graphs to analyze scalability.

---

## Setup Instructions

1. Clone the repository:
   in bash
   git clone <your-repo-url>
   cd graph-algo-mini-project-yourname

2. Create virtual environment:
    in bash
    python -m venv .venv

3. Activate environment:
    in bash
    .venv\Scripts\activate

4. Install dependencies:
    in bash
    pip install -r requirements.txt


## How to Run
Launch Jupyter Notebook:
    in terminal
    jupyter lab

Open:
notebooks/graph_realworld.ipynb

Run all cells to view implementations, outputs, and performance graphs.

## Key Observations
BFS and DFS have similar complexity but differ in traversal approach
Dijkstra performs faster than Bellman-Ford for large graphs
Bellman-Ford is useful for graphs with negative weights
Algorithm choice depends on problem constraints


## Project Structure
graph-algo-mini-project-yourname/
│
├── notebooks/
│   └── graph_realworld.ipynb
├── images/
├── README.md
├── requirements.txt
└── .gitignore


## Conclusion
This project highlights how different graph algorithms behave under varying conditions. Understanding their performance and limitations helps in selecting the right algorithm for practical problems.
