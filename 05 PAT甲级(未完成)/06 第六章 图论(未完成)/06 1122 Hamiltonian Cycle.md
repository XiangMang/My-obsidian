## [题目详情 - 1122 Hamiltonian Cycle (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805351814119424)

[1615. 哈密顿回路 - AcWing题库](https://www.acwing.com/problem/content/1617/)

The "Hamilton cycle problem" is to find a simple cycle that contains every vertex in a graph. Such a cycle is called a "Hamiltonian cycle".

In this problem, you are supposed to tell if a given cycle is a Hamiltonian cycle.

### Input Specification:

Each input file contains one test case. For each case, the first line contains 2 positive integers $N (2<N \leq 200)$, the number of vertices, and $M$, the number of edges in an undirected graph. Then $M$ lines follow, each describes an edge in the format `Vertex1 Vertex2`, where the vertices are numbered from 1 to $N$. The next line gives a positive integer $K$ which is the number of queries, followed by $K$ lines of queries, each in the format:

$n~V_1~V_2~ \dots ~ V_n$

where $n$ is the number of vertices in the list, and *V*$i$'s are the vertices on a path.

### Output Specification:

For each query, print in a line `YES` if the path does form a Hamiltonian cycle, or `NO` if not.

### Sample Input:

```in
6 10
6 2
3 4
1 5
2 5
3 1
4 1
1 6
6 3
1 2
4 5
6
7 5 1 4 3 6 2 5
6 5 1 4 3 6 2
9 6 2 1 6 3 4 5 2 6
4 1 2 5 1
7 6 1 3 4 5 2 6
7 6 1 2 5 4 3 1
```

### Sample Output:

```out
YES
NO
NO
NO
YES
NO
```

### Idea



### AC code

```cpp
```


*2023-01-01 周日*