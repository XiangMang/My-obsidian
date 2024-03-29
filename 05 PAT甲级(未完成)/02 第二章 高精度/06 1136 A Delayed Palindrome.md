## [题目详情 - 1136 A Delayed Palindrome (pintia.cn)](https://pintia.cn/problem-sets/994805342720868352/problems/994805345732378624)

[1629. 延迟的回文数 - AcWing题库](https://www.acwing.com/problem/content/1631/)

#回文数 #高精度 #vector 

Consider[^1] a positive integer $N$ written in standard notation[^2] with $k+1$ digits $a_i$ as $a_k⋯a_1a_0$ with $0≤a_i<10$ for all $i$ and $a_k>0$. Then $N$ is **palindromic** if and only if $a_i=a_{k−i}$ for all $i$. Zero is written $0$ and is also palindromic by definition[^3].

Non-palindromic numbers can be paired with palindromic ones via[^4] a series of operations. First, the non-palindromic number is reversed and the result is added to the original number. If the result is not a palindromic number, this is repeated[^5] until it gives a palindromic number. Such number is called a delayed[^6] palindrome. (Quoted from [this](https://en.wikipedia.org/wiki/Palindromic_number ))

Given any positive integer, you are supposed to find its paired palindromic number.

### Input Specification:

Each input file contains one test case which gives a positive integer no more than $1000$ digits.

### Output Specification:

For each test case, print line by line the process of finding the palindromic number. The format of each line is the following:

```
A + B = C
```

where `A` is the original number, `B` is the reversed `A`, and `C` is their sum. `A` starts being the input number, and this process[^7] ends until `C` becomes a palindromic number -- in this case we print in the last line `C is a palindromic number.`; or if a palindromic number cannot be found in 10 iterations[^8], print `Not found in 10 iterations.` instead.

### Sample Input 1:

```in
97152
```

### Sample Output 1:

```out
97152 + 25179 = 122331
122331 + 133221 = 255552
255552 is a palindromic number.
```

### Sample Input 2:

```in
196
```

### Sample Output 2:

```out
196 + 691 = 887
887 + 788 = 1675
1675 + 5761 = 7436
7436 + 6347 = 13783
13783 + 38731 = 52514
52514 + 41525 = 94039
94039 + 93049 = 187088
187088 + 880781 = 1067869
1067869 + 9687601 = 10755470
10755470 + 07455701 = 18211171
Not found in 10 iterations.
```

### Idea

详见:[[04 1024 Palindromic Number]]

### AC code

```cpp
#include <iostream>
#include <vector>

using namespace std;

vector<int> a, b, c;

bool check(vector<int>& a){
    for(int i = 0, j = a.size() - 1; i < j; i++, j--){
        if(a[i] != a[j]) return false;
    }
    return true;
}

vector<int> add(vector<int>& a, vector<int>& b){
    vector<int> c;
    int t = 0;
    for(int i = 0; i < a.size(); i++){
        t += a[i] + b[i];
        c.push_back(t % 10);
        t /= 10;
    }
    if(t) c.push_back(1);
    return c;
}

int main(void){

    string str;
    cin >> str;

    for(int i = str.size() - 1; i >= 0; i--) a.push_back(str[i] - '0');

    c = a;
    int cnt = 0;
    while(!check(c) && cnt < 10){
        vector<int> b(a.rbegin(), a.rend());
        c = add(a, b);
        for(int i = a.size() - 1; i >= 0; i--) cout << a[i];
        printf(" + ");
        for(int i = b.size() - 1; i >= 0; i--) cout << b[i];
        printf(" = ");
        for(int i = c.size() - 1; i >= 0; i--) cout << c[i];
        printf("\n");
        cnt++;
        a = c;
    }

    if(cnt >= 9){
        puts("Not found in 10 iterations.");
    }
    else{
        for(int i = 0; i < c.size(); i++) cout << c[i];
        printf(" is a palindromic number.\n");
    }

    return 0;
}
```


*2022-07-20 周三*

[^1]: consider $v.$ 考虑
[^2]: notation $n.$ (数学)标记系统,成套符号
[^3]: definition $n.$ 定义
[^4]: via $prep.$ 经由
[^5]: repeat $v.$ 重复
[^6]: delayed $adj.$ 延迟的
[^7]: process $n.$ 程序
[^8]: iterations $n.$ 迭代次数