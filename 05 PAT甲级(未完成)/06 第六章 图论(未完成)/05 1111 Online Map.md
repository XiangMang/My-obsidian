## [题目详情 - 1111 Online Map (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805358663417856)

[1601. 在线地图 - AcWing题库](https://www.acwing.com/problem/content/1603/)

Input our current position and a destination, an online map can recommend several paths. Now your job is to recommend two paths to your user: one is the shortest, and the other is the fastest. It is guaranteed that a path exists for any request.

### Input Specification:

Each input file contains one test case. For each case, the first line gives two positive integers $N (2 \leq N \leq 500)$, and $M$, being the total number of streets intersections on a map, and the number of streets, respectively. Then $M$ lines follow, each describes a street in the format:

```
V1 V2 one-way length time
```

where `V1` and `V2` are the indices (from 0 to $N-1$) of the two ends of the street; `one-way` is 1 if the street is one-way from `V1` to `V2`, or 0 if not; `length` is the length of the street; and `time` is the time taken to pass the street.

Finally a pair of source and destination is given.

### Output Specification:

For each case, first print the shortest path from the source to the destination with distance `D` in the format:

```
Distance = D: source -> v1 -> ... -> destination
```

Then in the next line print the fastest path with total time `T`:

```
Time = T: source -> w1 -> ... -> destination
```

In case the shortest path is not unique, output the fastest one among the shortest paths, which is guaranteed to be unique. In case the fastest path is not unique, output the one that passes through the fewest intersections, which is guaranteed to be unique.

In case the shortest and the fastest paths are identical, print them in one line in the format:

```
Distance = D; Time = T: source -> u1 -> ... -> destination
```

### Sample Input 1:

```in
10 15
0 1 0 1 1
8 0 0 1 1
4 8 1 1 1
3 4 0 3 2
3 9 1 4 1
0 6 0 1 1
7 5 1 2 1
8 5 1 2 1
2 3 0 2 2
2 1 1 1 1
1 3 0 3 1
1 4 0 1 1
9 7 1 3 1
5 1 0 5 2
6 5 1 1 2
3 5
```

### Sample Output 1:

```out
Distance = 6: 3 -> 4 -> 8 -> 5
Time = 3: 3 -> 1 -> 5
```

### Sample Input 2:

```in
7 9
0 4 1 1 1
1 6 1 1 3
2 6 1 1 1
2 5 1 2 2
3 0 0 1 1
3 1 1 1 3
3 2 1 1 2
4 5 0 2 2
6 5 1 1 2
3 5
```

### Sample Output 2:

```out
Distance = 3; Time = 4: 3 -> 2 -> 5
```

### Idea



### AC code

```cpp
```


*2023-01-01 周日*