## 硅谷live以太坊智能合约 第二课作业
这里是同学提交作业的目录

### 第二课：课后作业
完成今天的智能合约添加100ETH到合约中
- 加入十个员工，每个员工的薪水都是1ETH
每次加入一个员工后调用calculateRunway这个函数，并且记录消耗的gas是多少？Gas变化么？如果有 为什么？
- 如何优化calculateRunway这个函数来减少gas的消耗？
提交：智能合约代码，gas变化的记录，calculateRunway函数的优化

第一次
1. 22971 + 1699	
1. 23759 + 2487
1. 24547 + 3275	
1. 25335 + 4063
1. 26123 + 4851
1. 26911 + 5639
1. 27699 + 6427
1. 28487 + 7215
1. 29275 + 8003
1. 30063 + 8791

优化后 每次都是
22122 + 850

优化思路是添加员工的时候一起把工资算好，不用每次查询都算一遍。。。
