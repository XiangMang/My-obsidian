## [题目详情 - 1087 All Roads Lead to Rome (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805379664297984)

[1577. 条条大路通罗马 - AcWing题库](https://www.acwing.com/problem/content/1579/)

Indeed there are many different tourist routes from our city to Rome. You are supposed to find your clients the route with the least cost while gaining the most happiness.

### Input Specification:

Each input file contains one test case. For each case, the first line contains 2 positive integers $N (2 \leq N \leq 200)$, the number of cities, and $K$, the total number of routes between pairs of cities; followed by the name of the starting city. The next $N-1$ lines each gives the name of a city and an integer that represents the happiness one can gain from that city, except the starting city. Then $K$ lines follow, each describes a route between two cities in the format `City1 City2 Cost`. Here the name of a city is a string of 3 capital English letters, and the destination is always `ROM` which represents Rome.

### Output Specification:

For each test case, we are supposed to find the route with the least cost. If such a route is not unique, the one with the maximum happiness will be recommanded. If such a route is still not unique, then we output the one with the maximum average happiness -- it is guaranteed by the judge that such a solution exists and is unique.

Hence in the first line of output, you must print 4 numbers: the number of different routes with the least cost, the cost, the happiness, and the average happiness (take the integer part only) of the recommanded route. Then in the next line, you are supposed to print the route in the format `City1->City2->...->ROM`.

### Sample Input:

```in
6 7 HZH
ROM 100
PKN 40
GDN 55
PRS 95
BLN 80
ROM GDN 1
BLN ROM 1
HZH PKN 1
PRS ROM 2
BLN HZH 2
PKN GDN 1
HZH PRS 1
```

### Sample Output:

```out
3 3 195 97
HZH->PRS->ROM
```

### Idea



### AC code

```cpp
```


*2023-01-01 周日*