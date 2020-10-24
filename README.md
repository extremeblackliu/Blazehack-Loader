# Blazehack-Loader
运行时修复BlazeHack的一个Loader  
目前只修复了ClientState中的  
m_Events  
解决了当"round_start"开始的时候触发m_Events导致操作空内存然后闪退/卡死的问题  
ClientState还有很多表需要修复，我推荐的是在IDA中更改ClientState的数据结构来解决它   
这只是一个示例程序用于"在易语言中做到修复一个东西"  
只是单纯的patch了汇编代码  

# TODO:
修复其他ClientState结构,确保FakeLags显示以及其他功能正常  
优化代码,改进OEP调用  

![IMAGE](https://github.com/extremeblackliu/Blazehack-Loader/blob/main/bh.png)
