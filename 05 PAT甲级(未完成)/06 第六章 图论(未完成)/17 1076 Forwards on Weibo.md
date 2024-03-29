## [题目详情 - 1076 Forwards on Weibo (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805392092020736)

[1562. 微博转发 - AcWing题库](https://www.acwing.com/problem/content/1564/)

Weibo is known as the Chinese version of Twitter. One user on Weibo may have many followers, and may follow many other users as well. Hence a social network is formed with followers relations. When a user makes a post on Weibo, all his/her followers can view and forward his/her post, which can then be forwarded again by their followers. Now given a social network, you are supposed to calculate the maximum potential amount of forwards for any specific user, assuming that only $L$ levels of indirect followers are counted.

### Input Specification:

Each input file contains one test case. For each case, the first line contains 2 positive integers: $N ( \leq 1000)$, the number of users; and $L ( \leq 6)$, the number of levels of indirect followers that are counted. Hence it is assumed that all the users are numbered from 1 to $N$. Then $N$ lines follow, each in the format:

```
M[i] user_list[i]
```

where `M[i]` $( \leq 100)$ is the total number of people that `user[i]` follows; and `user_list[i]` is a list of the `M[i]` users that followed by `user[i]`. It is guaranteed that no one can follow oneself. All the numbers are separated by a space.

Then finally a positive $K$ is given, followed by $K$ `UserID`'s for query.

### Output Specification:

For each `UserID`, you are supposed to print in one line the maximum potential amount of forwards this user can trigger, assuming that everyone who can view the initial post will forward it once, and that only $L$ levels of indirect followers are counted.

### Sample Input:

```in
7 3
3 2 3 4
0
2 5 6
2 3 1
2 3 4
1 4
1 5
2 2 6
```

### Sample Output:

```out
4
5
```

### Idea



### AC code

```cpp
```


*2023-01-01 周日*