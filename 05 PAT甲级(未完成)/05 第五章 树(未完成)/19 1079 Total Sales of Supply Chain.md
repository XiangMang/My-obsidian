## [题目详情 - 1079 Total Sales of Supply Chain (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805388447170560)

[1565. 供应链总销售额 - AcWing题库](https://www.acwing.com/problem/content/1567/)

A supply chain is a network of retailers（零售商）, distributors（经销商）, and suppliers（供应商）-- everyone involved in moving a product from supplier to customer.

Starting from one root supplier, everyone on the chain buys products from one's supplier in a price $P$ and sell or distribute them in a price that is $r\%$ higher than $P$. Only the retailers will face the customers. It is assumed that each member in the supply chain has exactly one supplier except the root supplier, and there is no supply cycle.

Now given a supply chain, you are supposed to tell the total sales from all the retailers.

### Input Specification:

Each input file contains one test case. For each case, the first line contains three positive numbers: $N ( \leq 10^5)$, the total number of the members in the supply chain (and hence their ID's are numbered from 0 to $N−1$, and the root supplier's ID is 0); $P$, the unit price given by the root supplier; and $r$, the percentage rate of price increment for each distributor or retailer. Then $N$ lines follow, each describes a distributor or retailer in the following format:

$K_i~~ID[1]~~ID[2]~~\dots~~ID[K_i]$

where in the $i$-th line, $K_i$ is the total number of distributors or retailers who receive products from supplier $i$, and is then followed by the ID's of these distributors or retailers. $K_j$ being 0 means that the $j$-th member is a retailer, then instead the total amount of the product will be given after $K_j$. All the numbers in a line are separated by a space.

### Output Specification:

For each test case, print in one line the total sales we can expect from all the retailers, accurate up to 1 decimal place. It is guaranteed that the number will not exceed $10^{10}$.

### Sample Input:

```in
10 1.80 1.00
3 2 3 5
1 9
1 4
1 7
0 7
2 6 1
1 8
0 9
0 4
0 3
```

### Sample Output:

```out
42.4
```

### Idea



### AC code

```cpp
```


*2022-12-31 周六*