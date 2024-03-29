## [题目详情 - 1142 Maximal Clique (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805343979159552)

[1635. 最大团 - AcWing题库](https://www.acwing.com/problem/content/1637/)

A **clique** is a subset of vertices of an undirected graph such that every two distinct vertices in the clique are adjacent. A **maximal clique** is a clique that cannot be extended by including one more adjacent vertex. (Quoted from https://en.wikipedia.org/wiki/Clique_(graph_theory))

Now it is your job to judge if a given subset of vertices can form a maximal clique.

### Input Specification:

Each input file contains one test case. For each case, the first line gives two positive integers $Nv ( \leq  200)$, the number of vertices in the graph, and Ne, the number of undirected edges. Then Ne lines follow, each gives a pair of vertices of an edge. The vertices are numbered from 1 to $Nv$.

After the graph, there is another positive integer $M ( \leq  100)$. Then M lines of query follow, each first gives a positive number $K ( \leq  Nv)$, then followed by a sequence of K distinct vertices. All the numbers in a line are separated by a space.

### Output Specification:

For each of the $M$ queries, print in a line `Yes` if the given subset of vertices can form a maximal clique; or if it is a clique but not a **maximal clique**, print `Not Maximal`; or if it is not a clique at all, print `Not a Clique`.

### Sample Input:

```in
8 10
5 6
7 8
6 4
3 6
4 5
2 3
8 2
2 7
5 3
3 4
6
4 5 4 3 6
3 2 8 7
2 2 3
1 1
3 4 3 6
3 3 2 1
```

### Sample Output:

```out
Yes
Yes
Yes
Yes
Not Maximal
Not a Clique
```

### Idea



### AC code

```cpp
```


*2023-01-01 周日*