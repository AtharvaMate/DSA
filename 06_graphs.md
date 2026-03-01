# 🌐 Graphs (45 Problems)

[← Back to Main Guide](./google_interview_guide.md)

---

## BFS

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 1 | [#200. Number of Islands](https://leetcode.com/problems/number-of-islands/) | M | Grid BFS/DFS |
| 2 | [#994. Rotting Oranges](https://leetcode.com/problems/rotting-oranges/) | M | Multi-source BFS |
| 3 | [#286. Walls and Gates](https://leetcode.com/problems/walls-and-gates/) | M | Multi-source BFS |
| 4 | [#1091. Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/) | M | 8-directional BFS |
| 5 | [#127. Word Ladder](https://leetcode.com/problems/word-ladder/) | H | BFS word transform |
| 6 | [#126. Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | H | BFS + backtrack paths |
| 7 | [#752. Open the Lock](https://leetcode.com/problems/open-the-lock/) | M | BFS state space |
| 8 | [#1197. Minimum Knight Moves](https://leetcode.com/problems/minimum-knight-moves/) | M | BFS / bidirectional |
| 9 | [#815. Bus Routes](https://leetcode.com/problems/bus-routes/) | H | Route-level BFS |
| 10 | [#864. Shortest Path to Get All Keys](https://leetcode.com/problems/shortest-path-to-get-all-keys/) | H | BFS + bitmask state |

## DFS

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 11 | [#130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | M | Border DFS |
| 12 | [#417. Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/) | M | Reverse DFS from oceans |
| 13 | [#133. Clone Graph](https://leetcode.com/problems/clone-graph/) | M | DFS with hashmap |
| 14 | [#694. Number of Distinct Islands](https://leetcode.com/problems/number-of-distinct-islands/) | M | Path signature |
| 15 | [#695. Max Area of Island](https://leetcode.com/problems/max-area-of-island/) | M | DFS area counting |
| 16 | [#721. Accounts Merge](https://leetcode.com/problems/accounts-merge/) | M | DFS / Union-Find |

## Topological Sort

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 17 | [#207. Course Schedule](https://leetcode.com/problems/course-schedule/) | M | Cycle detection |
| 18 | [#210. Course Schedule II](https://leetcode.com/problems/course-schedule-ii/) | M | Topological ordering |
| 19 | [#269. Alien Dictionary](https://leetcode.com/problems/alien-dictionary/) | H | Build graph + topo sort |
| 20 | [#444. Sequence Reconstruction](https://leetcode.com/problems/sequence-reconstruction/) | M | Unique topo order |
| 21 | [#310. Minimum Height Trees](https://leetcode.com/problems/minimum-height-trees/) | M | Leaf peeling |
| 22 | [#1136. Parallel Courses](https://leetcode.com/problems/parallel-courses/) | M | BFS topo + levels |

## Union-Find

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 23 | [#323. Number of Connected Components](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) | M | Basic DSU |
| 24 | [#684. Redundant Connection](https://leetcode.com/problems/redundant-connection/) | M | Cycle in undirected |
| 25 | [#685. Redundant Connection II](https://leetcode.com/problems/redundant-connection-ii/) | H | Directed graph DSU |
| 26 | [#261. Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/) | M | Connected + acyclic |
| 27 | [#947. Most Stones Removed](https://leetcode.com/problems/most-stones-removed-with-same-row-or-column/) | M | Union by row/col |
| 28 | [#990. Satisfiability of Equality Equations](https://leetcode.com/problems/satisfiability-of-equality-equations/) | M | Union-Find grouping |
| 29 | [#1202. Smallest String With Swaps](https://leetcode.com/problems/smallest-string-with-swaps/) | M | Connected component sort |

## Shortest Path

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 30 | [#743. Network Delay Time](https://leetcode.com/problems/network-delay-time/) | M | Dijkstra's |
| 31 | [#787. Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/) | M | BFS / Bellman-Ford |
| 32 | [#1631. Path With Minimum Effort](https://leetcode.com/problems/path-with-minimum-effort/) | M | Binary search + BFS / Dijkstra |
| 33 | [#778. Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/) | H | Binary search + BFS |
| 34 | [#1334. Find the City With Smallest Number of Neighbors](https://leetcode.com/problems/find-the-city-with-the-smallest-number-of-neighbors-at-a-threshold-distance/) | M | Floyd-Warshall / Dijkstra |

## Advanced Graph

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 35 | [#1192. Critical Connections in a Network](https://leetcode.com/problems/critical-connections-in-a-network/) | H | Tarjan's bridges |
| 36 | [#332. Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | H | Hierholzer's Euler path |
| 37 | [#785. Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/) | M | 2-coloring BFS/DFS |
| 38 | [#886. Possible Bipartition](https://leetcode.com/problems/possible-bipartition/) | M | Bipartite check |
| 39 | [#399. Evaluate Division](https://leetcode.com/problems/evaluate-division/) | M | Weighted graph DFS |
| 40 | [#329. Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/) | H | DFS + memoization |
| 41 | [#909. Snakes and Ladders](https://leetcode.com/problems/snakes-and-ladders/) | M | BFS simulation |
| 42 | [#827. Making A Large Island](https://leetcode.com/problems/making-a-large-island/) | H | Component size + flip |
| 43 | [#934. Shortest Bridge](https://leetcode.com/problems/shortest-bridge/) | M | DFS + BFS |
| 44 | [#542. 01 Matrix](https://leetcode.com/problems/01-matrix/) | M | Multi-source BFS |
| 45 | [#841. Keys and Rooms](https://leetcode.com/problems/keys-and-rooms/) | M | DFS reachability |
