## [题目详情 - 1068 Find More Coins (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805402305150976)

[1554. 找更多硬币 - AcWing题库](https://www.acwing.com/problem/content/1556/)

Eva loves to collect coins from all over the universe, including some other planets like Mars. One day she visited a universal shopping mall which could accept all kinds of coins as payments. However, there was a special requirement of the payment: for each bill, she must pay the exact amount. Since she has as many as $10^4$ coins with her, she definitely needs your help. You are supposed to tell her, for any given amount of money, whether or not she can find some coins to pay for it.

### Input Specification:

Each input file contains one test case. For each case, the first line contains 2 positive numbers: `N` ( $\leq 10^4$, the total number of coins) and `M` ( $\leq 10^2$, the amount of money Eva has to pay). The second line contains `N` face values of the coins, which are all positive numbers. All the numbers in a line are separated by a space.

### Output Specification:

For each test case, print in one line the face values $V_1 \leq V_2 \leq \dots  \leq V_k$ such that $V_1+V_2+\dots +V_k=$`M`. All the numbers must be separated by a space, and there must be no extra space at the end of the line. If such a solution is not unique, output the smallest sequence. If there is no solution, output "No Solution" instead.

Note: sequence {A[1], A[2], ...} is said to be "smaller" than sequence {B[1], B[2], ...} if there exists $k \geq 1$ such that $A[i]=B[i]$ for all $i<k$, and $A[k] < B[k]$.

### Sample Input 1:

```in
8 9
5 9 8 7 2 3 4 1
```

### Sample Output 1:

```out
1 3 5
```

### Sample Input 2:

```
4 8
7 2 4 3
```

### Sample Output 2:

```
No Solution
```

### Idea



### AC code

```cpp
```


*2023-01-01 周日*