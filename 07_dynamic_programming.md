# 🧩 Dynamic Programming (50 Problems)

[← Back to Main Guide](./google_interview_guide.md)

---

## 1D DP

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 1 | [#70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | M | Fibonacci variant |
| 2 | [#198. House Robber](https://leetcode.com/problems/house-robber/) | M | Take/skip |
| 3 | [#213. House Robber II](https://leetcode.com/problems/house-robber-ii/) | M | Circular |
| 4 | [#91. Decode Ways](https://leetcode.com/problems/decode-ways/) | M | String partition DP |
| 5 | [#55. Jump Game](https://leetcode.com/problems/jump-game/) | M | Greedy / DP |
| 6 | [#45. Jump Game II](https://leetcode.com/problems/jump-game-ii/) | M | BFS-style greedy |
| 7 | [#279. Perfect Squares](https://leetcode.com/problems/perfect-squares/) | M | BFS / DP |
| 8 | [#322. Coin Change](https://leetcode.com/problems/coin-change/) | M | Unbounded knapsack |
| 9 | [#518. Coin Change II](https://leetcode.com/problems/coin-change-ii/) | M | Counting combinations |
| 10 | [#300. Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | M | DP + binary search |

## 2D / Grid DP

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 11 | [#62. Unique Paths](https://leetcode.com/problems/unique-paths/) | M | Grid DP |
| 12 | [#63. Unique Paths II](https://leetcode.com/problems/unique-paths-ii/) | M | Grid DP with obstacles |
| 13 | [#64. Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | M | Grid min-cost |
| 14 | [#120. Triangle](https://leetcode.com/problems/triangle/) | M | Bottom-up DP |
| 15 | [#221. Maximal Square](https://leetcode.com/problems/maximal-square/) | M | 2D DP squares |
| 16 | [#174. Dungeon Game](https://leetcode.com/problems/dungeon-game/) | H | Reverse DP |
| 17 | [#741. Cherry Pickup](https://leetcode.com/problems/cherry-pickup/) | H | 3D DP two paths |
| 18 | [#1463. Cherry Pickup II](https://leetcode.com/problems/cherry-pickup-ii/) | H | Two robots DP |

## String DP

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 19 | [#1143. Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) | M | Classic 2D |
| 20 | [#72. Edit Distance](https://leetcode.com/problems/edit-distance/) | M | Insert/delete/replace |
| 21 | [#115. Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/) | H | Counting DP |
| 22 | [#10. Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | H | DP with '.' and '*' |
| 23 | [#44. Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | H | DP pattern |

## Knapsack Variants

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 24 | [#416. Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | M | 0/1 knapsack |
| 25 | [#494. Target Sum](https://leetcode.com/problems/target-sum/) | M | DP count |
| 26 | [#1049. Last Stone Weight II](https://leetcode.com/problems/last-stone-weight-ii/) | M | Min subset diff |
| 27 | [#474. Ones and Zeroes](https://leetcode.com/problems/ones-and-zeroes/) | M | 2D knapsack |
| 28 | [#879. Profitable Schemes](https://leetcode.com/problems/profitable-schemes/) | H | 3D knapsack |

## Interval & Range DP

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 29 | [#312. Burst Balloons](https://leetcode.com/problems/burst-balloons/) | H | Interval DP |
| 30 | [#877. Stone Game](https://leetcode.com/problems/stone-game/) | M | Game theory DP |
| 31 | [#1130. Minimum Cost Tree From Leaf Values](https://leetcode.com/problems/minimum-cost-tree-from-leaf-values/) | M | Stack / interval DP |
| 32 | [#132. Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | H | Min cuts DP |
| 33 | [#664. Strange Printer](https://leetcode.com/problems/strange-printer/) | H | Interval DP merge |

## Stock Series

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 34 | [#122. Best Time to Buy and Sell Stock II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) | M | Greedy accumulation |
| 35 | [#123. Best Time to Buy and Sell Stock III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/) | H | State machine 2 txn |
| 36 | [#188. Best Time to Buy and Sell Stock IV](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/) | H | K transactions DP |
| 37 | [#309. Best Time with Cooldown](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) | M | State machine |
| 38 | [#714. Best Time with Transaction Fee](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) | M | State machine |

## Advanced DP

| # | Problem | Diff | Key Concept |
|---|---------|------|-------------|
| 39 | [#368. Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | M | LIS variant |
| 40 | [#673. Number of Longest Increasing Subsequence](https://leetcode.com/problems/number-of-longest-increasing-subsequence/) | M | LIS counting |
| 41 | [#354. Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | H | LIS 2D |
| 42 | [#1048. Longest String Chain](https://leetcode.com/problems/longest-string-chain/) | M | DP + hashmap |
| 43 | [#139. Word Break](https://leetcode.com/problems/word-break/) | M | DP + set |
| 44 | [#1000. Minimum Cost to Merge Stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/) | H | Interval DP |
| 45 | [#403. Frog Jump](https://leetcode.com/problems/frog-jump/) | H | DP + hashmap states |
| 46 | [#740. Delete and Earn](https://leetcode.com/problems/delete-and-earn/) | M | House robber on values |
| 47 | [#1220. Count Vowels Permutation](https://leetcode.com/problems/count-vowels-permutation/) | H | State machine DP |
| 48 | [#446. Arithmetic Slices II — Subsequence](https://leetcode.com/problems/arithmetic-slices-ii-subsequence/) | H | DP + hashmap |
| 49 | [#1335. Minimum Difficulty of a Job Schedule](https://leetcode.com/problems/minimum-difficulty-of-a-job-schedule/) | H | Partition DP |
| 50 | [#1473. Paint House III](https://leetcode.com/problems/paint-house-iii/) | H | 3D DP neighborhoods |
