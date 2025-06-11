TASK-1: UNDERSATNDING SEARCH ALGORITHMS:

This task demonstrates how to perform Breadth-First Search (BFS) and Depth-First Search (DFS) on an undirected graph, including disconnected components. It uses a class-based Python implementation for clarity and scalability.
Key Features

Graph is implemented using an adjacency list with defaultdict(list)

Supports adding edges

Includes:

bfs(start_node): Iterative BFS from a given start node

dfs(start_node): Recursive DFS from a given start node

bfs_full(): BFS traversal of the entire graph (even if disconnected)

dfs_full(): DFS traversal of the entire graph (even if disconnected)

BFS (Breadth-First Search) explores neighbors level by level using a queue.

DFS (Depth-First Search) explores as far as possible down each path using recursion (or a stack).
