## [题目详情 - 1130 Infix Expression (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805347921805312)

[1623. 中缀表达式 - AcWing题库](https://www.acwing.com/problem/content/1625/)

Given a syntax tree (binary), you are supposed to output the corresponding infix expression, with parentheses reflecting the precedences of the operators.

### Input Specification:

Each input file contains one test case. For each case, the first line gives a positive integer $N ( \leq  20)$ which is the total number of nodes in the syntax tree. Then N lines follow, each gives the information of a node (the $i$-th line corresponds to the $i$-th node) in the format:

```
data left_child right_child
```

where `data` is a string of no more than 10 characters, `left_child` and `right_child` are the indices of this node's left and right children, respectively. The nodes are indexed from 1 to N. The NULL link is represented by −1. The figures 1 and 2 correspond to the samples 1 and 2, respectively.

| ![infix1.JPG](https://images.ptausercontent.com/4d1c4a98-33cc-45ff-820f-c548845681ba.JPG) | ![infix2.JPG](https://images.ptausercontent.com/b5a3c36e-91ad-494a-8853-b46e1e8b60cc.JPG) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Figure 1                                                     | Figure 2                                                     |

### Output Specification:

For each case, print in a line the infix expression, with parentheses reflecting the precedences of the operators. Note that there must be no extra parentheses for the final expression, as is shown by the samples. There must be no space between any symbols.

### Sample Input 1:

```in
8
* 8 7
a -1 -1
* 4 1
+ 2 5
b -1 -1
d -1 -1
- -1 6
c -1 -1
```

### Sample Output 1:

```out
(a+b)*(c*(-d))
```

### Sample Input 2:

```in
8
2.35 -1 -1
* 6 1
- -1 4
% 7 8
+ 2 3
a -1 -1
str -1 -1
871 -1 -1
```

### Sample Output 2:

```out
(a*2.35)+(-(str%871))
```

### Idea



### AC code

```cpp
```

*2022-12-31 周六*