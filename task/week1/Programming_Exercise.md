## 程序设计能力练习题

- 请用 C++ 编写程序，直接使用 `g++` 编译。
- 开设此题的目的只是想让你熟悉基本的 C++ 和程序设计，多动动脑筋。
- 只要简单测试 Accepted 就可以得分，代码简洁可得满分。请独立认真完成。
- 可能需要先了解的知识：`std::string`、`std::vector`。。
- 只需要提交函数定义，请自行测试完整代码。

## 第一周题目 —— 最大公共后缀

### Description

编写一个函数来查找字符串数组中的最长公共后缀。

如果不存在公共前缀，返回空字符串""。

### Input
编写一个函数，接口如下:

```cpp
string longestCommon(vector<string>& strs);
```

### Output

返回最长的公共后缀

### Sample Input

```
ppp
pplpp
lpp
```

### Sample Output

```
pp
```