# DP题单

>题目整合自各大经典题单，其中 `力扣100+150+75` 就至少可以覆盖中大厂 **80%** 的算法题。
>
>本题单为：==**动态规划专项**==。
>
>**对于动态规划问题，可以拆解为如下五步曲，这五步都搞清楚了，才能说把动态规划真的掌握了！       ——出自《代码随想录》**
>
>1. 确定dp数组以及下标的含义
>2. 确定递推公式
>3. dp数组如何初始化
>4. 确定遍历顺序
>5. 举例推导dp数组





[TOC]







# 题目链接汇总

## LeetCode 热题 100

[62. 不同路径（东华OJ原题）](https://leetcode.cn/problems/unique-paths/)

[70. 爬楼梯](https://leetcode.cn/problems/climbing-stairs/)

[118. 杨辉三角](https://leetcode.cn/problems/pascals-triangle/)

[198. 打家劫舍](https://leetcode.cn/problems/house-robber/)

[279. 完全平方数](https://leetcode.cn/problems/perfect-squares/)

[322. 零钱兑换](https://leetcode.cn/problems/coin-change/)

[300. 最长递增子序列](https://leetcode.cn/problems/longest-increasing-subsequence/)

[152. 乘积最大子数组](https://leetcode.cn/problems/maximum-product-subarray/)

[416. 分割等和子集](https://leetcode.cn/problems/partition-equal-subset-sum/)

[32. 最长有效括号](https://leetcode.cn/problems/longest-valid-parentheses/)

[64. 最小路径和（类似25东华复试上机题）](https://leetcode.cn/problems/minimum-path-sum/)

[5. 最长回文子串](https://leetcode.cn/problems/longest-palindromic-substring/)

[1143. 最长公共子序列](https://leetcode.cn/problems/longest-common-subsequence/)

[139. 单词拆分（东华OJ原题）](https://leetcode.cn/problems/word-break/)

[121. 买卖股票的最佳时机（东华OJ原题）](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/)

[53. 最大子数组和](https://leetcode.cn/problems/maximum-subarray/)

[72. 编辑距离（东华OJ原题）](https://leetcode.cn/problems/edit-distance/)





## LeetCode面试经典 150 题

[122. 买卖股票的最佳时机 II](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/)

[123. 买卖股票的最佳时机 III](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/)

[188. 买卖股票的最佳时机 IV](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/)

[97. 交错字符串](https://leetcode.cn/problems/interleaving-string/)

[120. 三角形最小路径和](https://leetcode.cn/problems/triangle/)

[63. 不同路径 II（东华OJ原题）](https://leetcode.cn/problems/unique-paths-ii/)

[392. 判断子序列](https://leetcode.cn/problems/is-subsequence/)

[221. 最大正方形（东华OJ原题）](https://leetcode.cn/problems/maximal-square/)













## LeetCode 75

[714. 买卖股票的最佳时机含手续费](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/)

[746. 使用最小花费爬楼梯（东华OJ原题）](https://leetcode.cn/problems/min-cost-climbing-stairs/)

[790. 多米诺和托米诺平铺](https://leetcode.cn/problems/domino-and-tromino-tiling/)

[1137. 第 N 个泰波那契数](https://leetcode.cn/problems/n-th-tribonacci-number/)











## 代码随想录

[509. 斐波那契数](https://leetcode.cn/problems/fibonacci-number/)

[70. 爬楼梯](https://leetcode.cn/problems/climbing-stairs/)

[746. 使用最小花费爬楼梯](https://leetcode.cn/problems/min-cost-climbing-stairs/)

[343. 整数拆分（东华OJ原题）](https://leetcode.cn/problems/integer-break/)

[96. 不同的二叉搜索树](https://leetcode.cn/problems/unique-binary-search-trees/)

[1049. 最后一块石头的重量 II](https://leetcode.cn/problems/last-stone-weight-ii/)

[377. 组合总和 Ⅳ](https://leetcode.cn/problems/combination-sum-iv/)

[518. 零钱兑换 II](https://leetcode.cn/problems/coin-change-ii/)

[494. 目标和](https://leetcode.cn/problems/target-sum/)

[213. 打家劫舍 II](https://leetcode.cn/problems/house-robber-ii/)

[337. 打家劫舍 III](https://leetcode.cn/problems/house-robber-iii/)

[309. 买卖股票的最佳时机含冷冻期（东华OJ原题）](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/)

[674. 最长连续递增序列](https://leetcode.cn/problems/longest-continuous-increasing-subsequence/)

[718. 最长重复子数组](https://leetcode.cn/problems/maximum-length-of-repeated-subarray/)

[115. 不同的子序列（腾讯面试题）](https://leetcode.cn/problems/distinct-subsequences/)

[583. 两个字符串的删除操作](https://leetcode.cn/problems/delete-operation-for-two-strings/)

[647. 回文子串](https://leetcode.cn/problems/palindromic-substrings/)

[516. 最长回文子序列](https://leetcode.cn/problems/longest-palindromic-subsequence/)

[473. 火柴拼正方形](https://leetcode.cn/problems/matchsticks-to-square/)





## Acwing算法基础课

[01背包问题](https://www.acwing.com/problem/content/2/)

[完全背包问题](https://www.acwing.com/problem/content/3/)



## 牛客TOP101

[10. 正则表达式匹配](https://leetcode.cn/problems/regular-expression-matching/)

[93. 复原 IP 地址](https://leetcode.cn/problems/restore-ip-addresses/)

[91. 解码方法](https://leetcode.cn/problems/decode-ways/)





# 答案与笔记

## **LeetCode 热题 100**

### 62. 不同路径（东华OJ原题）









### 70. 爬楼梯

[70. 爬楼梯](https://leetcode.cn/problems/climbing-stairs/)









### 118. 杨辉三角







### 198. 打家劫舍









### 279. 完全平方数
### 322. 零钱兑换
### 300. 最长递增子序列
### 152. 乘积最大子数组
### 416. 分割等和子集
### 32. 最长有效括号
### 64. 最小路径和（25东华复试上机题）
### 5. 最长回文子串
### 1143. 最长公共子序列
### 139. 单词拆分（东华OJ原题）
### 121. 买卖股票的最佳时机（东华OJ原题）
### 53. 最大子数组和
### 72. 编辑距离（东华OJ原题）

## **LeetCode 面试经典 150 题**

### 122. 买卖股票的最佳时机 II
### 123. 买卖股票的最佳时机 III
### 188. 买卖股票的最佳时机 IV
### 97. 交错字符串
### 120. 三角形最小路径和
### 63. 不同路径 II（东华OJ原题）
### 392. 判断子序列
### 221. 最大正方形（东华OJ原题）

## **LeetCode 75**

### 714. 买卖股票的最佳时机含手续费
### 746. 使用最小花费爬楼梯（东华OJ原题）
### 790. 多米诺和托米诺平铺
### 1137. 第 N 个泰波那契数

## **代码随想录**

### 509. 斐波那契数

[509. 斐波那契数](https://leetcode.cn/problems/fibonacci-number/)

>**斐波那契数** （通常用 F(n) 表示）形成的序列称为 **斐波那契数列** 。该数列由 0 和 1 开始，后面的每一项数字都是前面两项数字的和。也就是：
>
>F(0) = 0，F(1) = 1
>
>F(n) = F(n - 1) + F(n - 2)，其中 n > 1
>
>给定 n ，请计算 F(n) 。
>
> 
>
>**示例 1：**
>
>**输入：**n = 2
>
>**输出：**1
>
>**解释：**F(2) = F(1) + F(0) = 1 + 0 = 1
>
>**示例 2：**
>
>**输入：**n = 3
>
>**输出：**2
>
>**解释：**F(3) = F(2) + F(1) = 1 + 1 = 2
>
>**示例 3：**
>
>**输入：**n = 4
>
>**输出：**3
>
>**解释：**F(4) = F(3) + F(2) = 2 + 1 = 3
>
> 
>
>**提示：**
>
>- 0 <= n <= 30



思路：



```C++
class Solution {
public:
    int fib(int n) {
        int dp[31] = {};
        dp[1] = 1;
        for(int i = 2; i <= n; i++)
            dp[i] = dp[i - 1] + dp[i - 2];
        return dp[n];
    }
};
```





















### 746. 使用最小花费爬楼梯











### 343. 整数拆分（东华OJ原题）

[343. 整数拆分（东华OJ原题）](https://leetcode.cn/problems/integer-break/)





### 96. 不同的二叉搜索树

[96. 不同的二叉搜索树](https://leetcode.cn/problems/unique-binary-search-trees/)





### 1049. 最后一块石头的重量 II

[1049. 最后一块石头的重量 II](https://leetcode.cn/problems/last-stone-weight-ii/)





### 377. 组合总和 Ⅳ









### 518. 零钱兑换 II
### 494. 目标和
### 213. 打家劫舍 II
### 337. 打家劫舍 III
### 309. 买卖股票的最佳时机含冷冻期（东华OJ原题）
### 674. 最长连续递增序列
### 718. 最长重复子数组
### 115. 不同的子序列（腾讯面试题）
### 583. 两个字符串的删除操作
### 647. 回文子串
### 516. 最长回文子序列
### 473. 火柴拼正方形

## **Acwing 算法基础课**

### 01 背包问题
### 完全背包问题

## **牛客 TOP101**

### 10. 正则表达式匹配
### 93. 复原 IP 地址
### 91. 解码方法







































































































































































































































































































