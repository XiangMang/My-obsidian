## [题目详情 - 1151 LCA in a Binary Tree (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/1038430130011897856)

[1644. 二叉树中的最低公共祖先 - AcWing题库](https://www.acwing.com/problem/content/1646/)

The lowest common ancestor (LCA) of two nodes U and V in a tree is the deepest node that has both U and V as descendants.

Given any two nodes in a binary tree, you are supposed to find their LCA.

### Input Specification:

Each input file contains one test case. For each case, the first line gives two positive integers: $M ( \leq  1,000)$, the number of pairs of nodes to be tested; and $N ( \leq  10,000)$, the number of keys in the binary tree, respectively. In each of the following two lines, N distinct integers are given as the inorder and preorder traversal sequences of the binary tree, respectively. It is guaranteed that the binary tree can be uniquely determined by the input sequences. Then M lines follow, each contains a pair of integer keys U and V. All the keys are in the range of **int**.

### Output Specification:

For each given pair of U and V, print in a line `LCA of U and V is A.` if the LCA is found and `A` is the key. But if `A` is one of U and V, print `X is an ancestor of Y.` where `X` is `A` and `Y` is the other node. If U or V is not found in the binary tree, print in a line `ERROR: U is not found.` or `ERROR: V is not found.` or `ERROR: U and V are not found.`.

### Sample Input:

```in
6 8
7 2 3 4 6 5 1 8
5 3 7 2 6 4 8 1
2 6
8 1
7 9
12 -3
0 8
99 99
```

### Sample Output:

```out
LCA of 2 and 6 is 3.
8 is an ancestor of 1.
ERROR: 9 is not found.
ERROR: 12 and -3 are not found.
ERROR: 0 is not found.
ERROR: 99 and 99 are not found.
```

### Idea



### AC code

```cpp
```


*2022-12-31 周六*