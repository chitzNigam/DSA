# 🧱 User-Defined Data Structures (Complete List)

## 🧩 1. Basic User-Defined Types

| Structure  | Description                           | Languages         |
|------------|----------------------------------------|-------------------|
| `struct`   | Groups variables of different types    | C, C++            |
| `class`    | Encapsulates data and behavior         | C++, Java, Python |
| `union`    | Memory-efficient variable grouping     | C, C++            |
| `enum`     | Defines named constant values          | C, Java, Python   |

---

## 📦 2. Common Abstract Data Types (ADTs)

| Structure           | Description                            |
|--------------------|----------------------------------------|
| Stack              | LIFO (Last-In, First-Out)              |
| Queue              | FIFO (First-In, First-Out)             |
| Deque              | Double-ended queue                     |
| Linked List        | Sequence of nodes                      |
| Hash Table         | Key-value mapping using hash function  |
| Heap (Min/Max)     | Priority queue structure               |
| Trie               | Prefix tree for fast string search     |
| Graph              | Nodes and edges                        |
| Tree               | Hierarchical structure                 |
| Binary Search Tree | Ordered binary tree                    |

---

## 🔁 3. Linked List Variants

| Type                   | Description                                |
|------------------------|--------------------------------------------|
| Singly Linked List     | One direction (`node -> next`)             |
| Doubly Linked List     | Two directions (`prev <-> node <-> next`)  |
| Circular Linked List   | Last node links to head (circular loop)    |

---

## 🌳 4. Tree Variants

| Structure               | Description                               |
|------------------------|-------------------------------------------|
| Binary Tree            | Each node has ≤ 2 children                 |
| Binary Search Tree     | Left < Root < Right                        |
| AVL Tree               | Self-balancing BST using rotations         |
| Red-Black Tree         | Balanced BST using color rules             |
| Splay Tree             | Self-adjusting BST                         |
| Treap                  | BST + Heap properties                      |
| Segment Tree           | Efficient range query/update               |
| Segment Tree (Lazy)    | Optimized for frequent range updates       |
| Fenwick Tree (BIT)     | Efficient prefix sums                      |
| Trie                   | Prefix tree for strings                    |
| Suffix Tree/Array      | Fast pattern matching                      |
| K-D Tree               | Multidimensional search                    |
| Range Tree             | 2D/3D range queries                        |
| Interval Tree          | Queries for overlapping intervals          |
| Cartesian Tree         | Binary heap + in-order traversal           |
| Rope                   | Tree of strings for efficient editing      |
| B-Tree / B+ Tree       | Multi-way balanced tree (disk access)      |
| Van Emde Boas Tree     | Fast lookup for bounded integers           |

---

## 🌐 5. Graph-Related Structures

| Structure              | Description                               |
|------------------------|-------------------------------------------|
| Adjacency List         | Maps nodes to neighbors                   |
| Adjacency Matrix       | 2D matrix representation of graph edges   |
| DFS Traversal          | Depth-first search                        |
| BFS Traversal          | Breadth-first search                      |
| Disjoint Set (Union-Find) | Tracks components / sets              |
| Aho-Corasick Trie      | Multi-pattern string matching             |

---

## 🧠 6. Specialized / Hybrid Data Structures

| Structure              | Description                               |
|------------------------|-------------------------------------------|
| Skip List              | Layered linked list with fast operations  |
| Bloom Filter           | Probabilistic membership set              |
| LRU Cache              | Least recently used eviction              |
| BitSet / Bit Vector    | Compact array of bits                     |
| Quad Tree              | Spatial partitioning for 2D space         |
| Octree                 | Spatial partitioning for 3D space         |
| Suffix Automaton       | Compressed suffix trie                    |
| Discretization         | Coordinate compression technique          |

---

## ✅ Summary by Category

| Category                 | Examples                                   |
|--------------------------|--------------------------------------------|
| Basic Types              | `struct`, `class`, `union`, `enum`         |
| Linear ADTs              | Stack, Queue, Linked List, Deque           |
| Non-Linear ADTs          | Trees, Graphs, Tries, Heaps                |
| Self-Balancing Trees     | AVL, Red-Black, Splay, Treap               |
| Range/Indexing Trees     | Segment Tree, BIT, B-Tree, Interval Tree   |
| String Matching          | Trie, Aho-Corasick, Suffix Tree/Array      |
| Specialized Structures   | Rope, Bloom Filter, LRU Cache, Skip List   |
| Spatial Structures       | Quad Tree, Octree, K-D Tree                |
| Graph Structures         | DFS, BFS, Union-Find, Adjacency Models     |

---
