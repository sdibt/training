### Info
* 英文队名KaoDeiQuanHui
* 中文队名考得全会！！
* 队员1 赵晨阳
* 队员2 刘鑫程
* 队员3 边浩东

### 比赛地址
> http://acm.sdibt.edu.cn/vjudge/contest/view.action?cid=2120#overview
### 做出来的题目
ADH
#### A

* 题意:题意：上下两行对应，如果都相等输出Ｙ，否则输出Ｎ．
#### B
* 题意：让B都移到左边，W移到左边,相邻两个交换花费a-b钱，不相邻花费a的钱，求最小的花费．
* 思路：将需要交换的号码分到两个数组中，求每一步的最优解．

### 补的题目

#### H
* 题意：找最小的一个值，每两个数要么是abs(i-j)，要么是 24-abs(i-j)，求出最小的和。

* 思路：先sort排序，然后从头两个一对，算出答案，将第一个移到最后一个，在计算一遍，取最小。
#### C
* 题意：找出字符串的子串有几个是能整除3的，输出个数。
* 思路：用dp数组标记一下，dp[0]存的是余数为0的个数  dp[1]存的是余数为1的个数   dp[2]存的是余数为2的个数，每一次根据该位余数的个数计算总和，每次遇到字母就要请0。

举个例子：字符串3 4 5 3 0

默认转换为10进制       3    4     5    3     0
该位的余数             0    1     2    0     0
dp[0]                 1    0     2    3     4
dp[1]                 0    2     0    0     0
dp[2]                 0    0     1    1     1
解释一下怎么来的 第一列很简单不用解释，第二列中该位除以3余数为1 所以dp[0]，是在1的基础上找到余数为0的个数，就需要找上一个余数为2的个数，
dp[1]，是在余数为1的基础上得到余数为1的个数，上一个余数为0的个数加本身，dp[2]是在1的基础上找到余数为2的个数，需要找上一个余数为1的个数。

