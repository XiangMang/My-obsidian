## [题目详情 - 1131 Subway Map (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805347523346432)

[1624. 地铁地图 - AcWing题库](https://www.acwing.com/problem/content/1626/)

In the big cities, the subway systems always look so complex to the visitors. To give you some sense, the following figure shows the map of Beijing subway. Now you are supposed to help people with your computer skills! Given the starting position of your user, your task is to find the quickest way to his/her destination.

![[Subway Map配图_1.jpg]]

### Input Specification:

Each input file contains one test case. For each case, the first line contains a positive integer $N ( \leq  100)$, the number of subway lines. Then $N$ lines follow, with the $i$-th $(i=1, \dots ,N)$ line describes the $i$-th subway line in the format:

$M~S[1]~S[2]~\dots~S[M]$

where $M ( \leq  100)$ is the number of stops, and S[$i$]'s $(i=1, \dots ,M)$ are the indices of the stations (the indices are 4-digit numbers from 0000 to 9999) along the line. It is guaranteed that the stations are given in the correct order -- that is, the train travels between S[$i$] and S[$i$+1] $(i=1, \dots ,M−1)$ without any stop.

Note: It is possible to have loops, but not self-loop (no train starts from S and stops at S without passing through another station). Each station interval belongs to a unique subway line. Although the lines may cross each other at some stations (so called "transfer stations"), no station can be the conjunction of more than 5 lines.

After the description of the subway, another positiv=e integer $K ( \leq  10)$ is given. Then $K$ lines follow, each gives a query from your user: the two indices as the starting station and the destination, respectively.

The following figure shows the sample map.

![[Subway Map配图_2.jpg]]

Note: It is guaranteed that all the stations are reachable, and all the queries consist of legal station numbers.

### Output Specification:

For each query, first print in a line the minimum number of stops. Then you are supposed to show the optimal path in a friendly format as the following:

```
Take Line#X1 from S1 to S2.
Take Line#X2 from S2 to S3.
......
```

where `X`$i$'s are the line numbers and `S`$i$'s are the station indices. Note: Besides the starting and ending stations, only the transfer stations shall be printed.

If the quickest path is not unique, output the one with the minimum number of transfers, which is guaranteed to be unique.

### Sample Input:

```in
4
7 1001 3212 1003 1204 1005 1306 7797
9 9988 2333 1204 2006 2005 2004 2003 2302 2001
13 3011 3812 3013 3001 1306 3003 2333 3066 3212 3008 2302 3010 3011
4 6666 8432 4011 1306
3
3011 3013
6666 2001
2004 3001
```

### Sample Output:

```out
2
Take Line#3 from 3011 to 3013.
10
Take Line#4 from 6666 to 1306.
Take Line#3 from 1306 to 2302.
Take Line#2 from 2302 to 2001.
6
Take Line#2 from 2004 to 1204.
Take Line#1 from 1204 to 1306.
Take Line#3 from 1306 to 3001.
```

### Idea



### AC code

```cpp
```


*2023-01-01 周日*