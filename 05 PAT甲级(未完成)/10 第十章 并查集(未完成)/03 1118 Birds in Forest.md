## [题目详情 - 1118 Birds in Forest (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805354108403712)

[1608. 森林里的鸟 - AcWing题库](https://www.acwing.com/problem/content/1610/)

Some scientists took pictures of thousands of birds in a forest. Assume that all the birds appear in the same picture belong to the same tree. You are supposed to help the scientists to count the maximum number of trees in the forest, and for any pair of birds, tell if they are on the same tree.

### Input Specification:

Each input file contains one test case. For each case, the first line contains a positive number $N ( \leq 10^4)$ which is the number of pictures. Then N lines follow, each describes a picture in the format:

$K~B_1~B_2~\dots~B_K$

where $K$ is the number of birds in this picture, and $B_i$'s are the indices of birds. It is guaranteed that the birds in all the pictures are numbered continuously from 1 to some number that is no more than $10^4$.

After the pictures there is a positive number $Q ( \leq 10^4)$ which is the number of queries. Then $Q$ lines follow, each contains the indices of two birds.

### Output Specification:

For each test case, first output in a line the maximum possible number of trees and the number of birds. Then for each query, print in a line `Yes` if the two birds belong to the same tree, or `No` if not.

### Sample Input:

```in
4
3 10 1 2
2 3 4
4 1 5 7 8
3 9 6 4
2
10 5
3 7
```

### Sample Output:

```out
2 10
Yes
No
```

### Idea



### AC code

```cpp
```


*2023-01-01 周日*