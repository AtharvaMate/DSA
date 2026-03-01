# 🌳 Trees & BST (40 Problems)

[← Back to Main Guide](./google_interview_guide.md)

---

## Traversal & Path

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 1 | [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | M | BFS level-by-level |
| 2 | [Binary Tree Zigzag Level Order](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) | M | BFS + direction flip |
| 3 | [Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) | M | BFS last per level |
| 4 | [Vertical Order Traversal](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) | H | Column + row sorting |
| 5 | [Path Sum II](https://leetcode.com/problems/path-sum-ii/) | M | DFS path tracking |
| 6 | [Path Sum III](https://leetcode.com/problems/path-sum-iii/) | M | Prefix sum on tree |
| 7 | [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | H | DFS global max |
| 8 | [Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/) | M | DFS accumulation |
| 9 | [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | M | Height-based DFS |

## Construction & Transformation

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 10 | [Construct Binary Tree from Preorder and Inorder](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | M | Recursive partition |
| 11 | [Construct Binary Tree from Inorder and Postorder](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) | M | Recursive partition |
| 12 | [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | M | Morris / reverse preorder |
| 13 | [Populating Next Right Pointers](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/) | M | BFS or constant space |
| 14 | [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | H | BFS/DFS encoding |
| 15 | [Maximum Width of Binary Tree](https://leetcode.com/problems/maximum-width-of-binary-tree/) | M | BFS with indexing |

## LCA & Ancestors

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 16 | [Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | M | Recursive LCA |
| 17 | [LCA of a Binary Tree III](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree-iii/) | M | Two pointer |
| 18 | [LCA of Deepest Leaves](https://leetcode.com/problems/lowest-common-ancestor-of-deepest-leaves/) | M | DFS depth tracking |

## BST Operations

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 19 | [Validate BST](https://leetcode.com/problems/validate-binary-search-tree/) | M | Range validation |
| 20 | [Kth Smallest Element in BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | M | Inorder traversal |
| 21 | [Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/) | M | Successor/predecessor |
| 22 | [Convert BST to Sorted DLL](https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/) | M | Inorder threading |
| 23 | [Recover Binary Search Tree](https://leetcode.com/problems/recover-binary-search-tree/) | M | Inorder anomaly |
| 24 | [Inorder Successor in BST](https://leetcode.com/problems/inorder-successor-in-bst/) | M | BST search |

## Advanced Tree

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 25 | [Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/) | M | Binary search on tree |
| 26 | [House Robber III](https://leetcode.com/problems/house-robber-iii/) | M | DP on tree |
| 27 | [All Nodes Distance K in Binary Tree](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/) | M | Convert to graph + BFS |
| 28 | [Boundary of Binary Tree](https://leetcode.com/problems/boundary-of-binary-tree/) | M | Left + leaves + right |
| 29 | [Binary Tree Cameras](https://leetcode.com/problems/binary-tree-cameras/) | H | Greedy DFS |
| 30 | [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | M | Recursive matching |
| 31 | [Most Frequent Subtree Sum](https://leetcode.com/problems/most-frequent-subtree-sum/) | M | DFS + hashmap |

## N-ary & Special Trees

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 32 | [N-ary Tree Level Order](https://leetcode.com/problems/n-ary-tree-level-order-traversal/) | M | BFS generalized |
| 33 | [Serialize and Deserialize N-ary Tree](https://leetcode.com/problems/serialize-and-deserialize-n-ary-tree/) | H | Child count encoding |
| 34 | [Encode N-ary Tree to Binary Tree](https://leetcode.com/problems/encode-n-ary-tree-to-binary-tree/) | H | Left-child right-sibling |
| 35 | [Maximum Depth of N-ary Tree](https://leetcode.com/problems/maximum-depth-of-n-ary-tree/) | M | DFS/BFS |
| 36 | [Complete Binary Tree Inserter](https://leetcode.com/problems/complete-binary-tree-inserter/) | M | BFS design |
| 37 | [Check Completeness of Binary Tree](https://leetcode.com/problems/check-completeness-of-a-binary-tree/) | M | BFS null detection |
| 38 | [Longest Univalue Path](https://leetcode.com/problems/longest-univalue-path/) | M | DFS with value matching |
| 39 | [Distribute Coins in Binary Tree](https://leetcode.com/problems/distribute-coins-in-binary-tree/) | M | Post-order excess flow |
| 40 | [Smallest String Starting From Leaf](https://leetcode.com/problems/smallest-string-starting-from-leaf/) | M | DFS string comparison |
