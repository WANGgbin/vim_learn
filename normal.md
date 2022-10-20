描述 vim 中 normal 命令的使用.

`normal` 用于在命令模式中执行常规模式指令,具体可以参考`:help normal`. normal 的格式为:`[range]norm[al] {commands}`.
- range

    表示范围: `%` 表示全文, `n,m` 表示 n-m 行

- commands

    表示正常模式下的操作

例子:
- 比如,给每一行末尾插入',',则可以`:%normal A,`