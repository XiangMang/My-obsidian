## [题目详情 - 1119 Pre- and Post-order Traversals (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805353470869504)

[1609. 前序和后序遍历 - AcWing题库](https://www.acwing.com/problem/content/1611/)

Suppose that all the keys in a binary tree are distinct positive integers. A unique binary tree can be determined by a given pair of postorder and inorder traversal sequences, or preorder and inorder traversal sequences. However, if only the postorder and preorder traversal sequences are given, the corresponding tree may no longer be unique.

Now given a pair of postorder and preorder traversal sequences, you are supposed to output the corresponding inorder traversal sequence of the tree. If the tree is not unique, simply output any one of them.

### Input Specification:

Each input file contains one test case. For each case, the first line gives a positive integer $N ( \leq  30)$, the total number of nodes in the binary tree. The second line gives the preorder sequence and the third line gives the postorder sequence. All the numbers in a line are separated by a space.

### Output Specification:

For each test case, first printf in a line `Yes` if the tree is unique, or `No` if not. Then print in the next line the inorder traversal sequence of the corresponding binary tree. If the solution is not unique, any answer would do. It is guaranteed that at least one solution exists. All the numbers in a line must be separated by exactly one space, and there must be no extra space at the end of the line.

### Sample Input 1:

```in
7
1 2 3 4 6 7 5
2 6 7 4 5 3 1
```

### Sample Output 1:

```out
Yes
2 1 6 4 7 3 5
```

### Sample Input 2:

```in
4
1 2 3 4
2 4 3 1
```

### Sample Output 2:

```out
No
2 1 3 4
```

### Idea



### AC code

```cpp
```


*2022-12-31 周六*