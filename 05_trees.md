# 🌳 Trees & BST (40 Problems)

[← Back to Main Guide](./google_interview_guide.md)

---

## Traversal & Path

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 1 | [#102. Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | M | BFS level-by-level |
| 2 | [#103. Binary Tree Zigzag Level Order](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) | M | BFS + direction flip |
| 3 | [#199. Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) | M | BFS last per level |
| 4 | [#987. Vertical Order Traversal](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) | H | Column + row sorting |
| 5 | [#113. Path Sum II](https://leetcode.com/problems/path-sum-ii/) | M | DFS path tracking |
| 6 | [#437. Path Sum III](https://leetcode.com/problems/path-sum-iii/) | M | Prefix sum on tree |
| 7 | [#124. Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | H | DFS global max |
| 8 | [#129. Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/) | M | DFS accumulation |
| 9 | [#543. Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | M | Height-based DFS |

## Construction & Transformation

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 10 | [#105. Construct Binary Tree from Preorder and Inorder](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | M | Recursive partition |
| 11 | [#106. Construct Binary Tree from Inorder and Postorder](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) | M | Recursive partition |
| 12 | [#114. Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | M | Morris / reverse preorder |
| 13 | [#117. Populating Next Right Pointers](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/) | M | BFS or constant space |
| 14 | [#297. Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | H | BFS/DFS encoding |
| 15 | [#662. Maximum Width of Binary Tree](https://leetcode.com/problems/maximum-width-of-binary-tree/) | M | BFS with indexing |

## LCA & Ancestors

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 16 | [#236. Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | M | Recursive LCA |
| 17 | [#1650. LCA of a Binary Tree III](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree-iii/) | M | Two pointer |
| 18 | [#1123. LCA of Deepest Leaves](https://leetcode.com/problems/lowest-common-ancestor-of-deepest-leaves/) | M | DFS depth tracking |

## BST Operations

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 19 | [#98. Validate BST](https://leetcode.com/problems/validate-binary-search-tree/) | M | Range validation |
| 20 | [#230. Kth Smallest Element in BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | M | Inorder traversal |
| 21 | [#450. Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/) | M | Successor/predecessor |
| 22 | [#426. Convert BST to Sorted DLL](https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/) | M | Inorder threading |
| 23 | [#99. Recover Binary Search Tree](https://leetcode.com/problems/recover-binary-search-tree/) | M | Inorder anomaly |
| 24 | [#285. Inorder Successor in BST](https://leetcode.com/problems/inorder-successor-in-bst/) | M | BST search |

## Advanced Tree

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 25 | [#222. Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/) | M | Binary search on tree |
| 26 | [#337. House Robber III](https://leetcode.com/problems/house-robber-iii/) | M | DP on tree |
| 27 | [#863. All Nodes Distance K in Binary Tree](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/) | M | Convert to graph + BFS |
| 28 | [#545. Boundary of Binary Tree](https://leetcode.com/problems/boundary-of-binary-tree/) | M | Left + leaves + right |
| 29 | [#968. Binary Tree Cameras](https://leetcode.com/problems/binary-tree-cameras/) | H | Greedy DFS |
| 30 | [#572. Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | M | Recursive matching |
| 31 | [#508. Most Frequent Subtree Sum](https://leetcode.com/problems/most-frequent-subtree-sum/) | M | DFS + hashmap |

## N-ary & Special Trees

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 32 | [#429. N-ary Tree Level Order](https://leetcode.com/problems/n-ary-tree-level-order-traversal/) | M | BFS generalized |
| 33 | [#428. Serialize and Deserialize N-ary Tree](https://leetcode.com/problems/serialize-and-deserialize-n-ary-tree/) | H | Child count encoding |
| 34 | [#431. Encode N-ary Tree to Binary Tree](https://leetcode.com/problems/encode-n-ary-tree-to-binary-tree/) | H | Left-child right-sibling |
| 35 | [#559. Maximum Depth of N-ary Tree](https://leetcode.com/problems/maximum-depth-of-n-ary-tree/) | M | DFS/BFS |
| 36 | [#919. Complete Binary Tree Inserter](https://leetcode.com/problems/complete-binary-tree-inserter/) | M | BFS design |
| 37 | [#958. Check Completeness of Binary Tree](https://leetcode.com/problems/check-completeness-of-a-binary-tree/) | M | BFS null detection |
| 38 | [#687. Longest Univalue Path](https://leetcode.com/problems/longest-univalue-path/) | M | DFS with value matching |
| 39 | [#979. Distribute Coins in Binary Tree](https://leetcode.com/problems/distribute-coins-in-binary-tree/) | M | Post-order excess flow |
| 40 | [#988. Smallest String Starting From Leaf](https://leetcode.com/problems/smallest-string-starting-from-leaf/) | M | DFS string comparison |
