## [题目详情 - 1139 First Contact (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/exam/problems/994805344776077312)

[1632. 第一次接触 - AcWing题库](https://www.acwing.com/problem/content/1634/)

Unlike in nowadays, the way that boys and girls expressing their feelings of love was quite subtle in the early years. When a boy A had a crush on a girl B, he would usually not contact her directly in the first place. Instead, he might ask another boy C, one of his close friends, to ask another girl D, who was a friend of both B and C, to send a message to B -- quite a long shot, isn't it? Girls would do analogously.

Here given a network of friendship relations, you are supposed to help a boy or a girl to list all their friends who can possibly help them making the first contact.

### Input Specification:

Each input file contains one test case. For each case, the first line gives two positive integers $N (1 < N  \leq  300)$ and $M$, being the total number of people and the number of friendship relations, respectively. Then $M$ lines follow, each gives a pair of friends. Here a person is represented by a 4-digit ID. To tell their genders, we use a negative sign to represent girls.

After the relations, a positive integer $K ( \leq  100)$ is given, which is the number of queries. Then $K$ lines of queries follow, each gives a pair of lovers, separated by a space. It is assumed that the first one is having a crush on the second one.

### Output Specification:

For each query, first print in a line the number of different pairs of friends they can find to help them, then in each line print the IDs of a pair of friends.

If the lovers A and B are of opposite genders, you must first print the friend of A who is of the same gender of A, then the friend of B, who is of the same gender of B. If they are of the same gender, then both friends must be in the same gender as theirs. It is guaranteed that each person has only one gender.

The friends must be printed in non-decreasing order of the first IDs, and for the same first ones, in increasing order of the seconds ones.

### Sample Input:

```in
10 18
-2001 1001
-2002 -2001
1004 1001
-2004 -2001
-2003 1005
1005 -2001
1001 -2003
1002 1001
1002 -2004
-2004 1001
1003 -2002
-2003 1003
1004 -2002
-2001 -2003
1001 1003
1003 -2001
1002 -2001
-2002 -2003
5
1001 -2001
-2003 1001
1005 -2001
-2002 -2004
1111 -2003
```

### Sample Output:

```out
4
1002 2004
1003 2002
1003 2003
1004 2002
4
2001 1002
2001 1003
2002 1003
2002 1004
0
1
2003 2001
0
```

### Idea



### AC code

```cpp
```


*2023-01-01 周日*