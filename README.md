# linux常用命令系列

## 介绍
linux常用命令系列包含每种常用命令的由来用法示例详解

 
## [linux常用命令系列](https://zhuanlan.zhihu.com/p/690059861/)

1. [【Linux常用命令系列】SSH-KEYGEN 手册](https://zhuanlan.zhihu.com/p/696004618)
2. [【Linux常用命令系列】linux test由来示例用法权威详解](https://zhuanlan.zhihu.com/p/666662935)
3. [【Linux常用命令系列】 apt-get 由来命令选项示例详解](https://zhuanlan.zhihu.com/p/682095213)
4. [【Linux常用命令系列】Linux sudo用法示例权威详解](https://zhuanlan.zhihu.com/p/666471591)
5. [【Linux常用命令系列】linux test由来示例用法权威详解](https://zhuanlan.zhihu.com/p/666662935)
6. [【Linux常用命令系列】linux cp由来示例用法详解](https://zhuanlan.zhihu.com/p/666660725)
7. [【Linux常用命令系列】linux sed由来用法示例权威详解](https://zhuanlan.zhihu.com/p/666661176)
8. [【Linux常用命令系列】linux useradd由来用法示例权威详解](https://zhuanlan.zhihu.com/p/666661963)
9. [【Linux常用命令系列】linux vi由来用法示例权威详解](https://zhuanlan.zhihu.com/p/666662475)
10. [【Linux常用命令系列】 unzip用法参数选项示例](https://zhuanlan.zhihu.com/p/682600829)
11. [【Linux常用命令系列】linux Trap: 由来用法示例最佳实践详解](https://zhuanlan.zhihu.com/p/666871419)?
12. [【Linux常用命令系列】Rsync命令由来原理选项用法示例详解](https://zhuanlan.zhihu.com/p/666871567)
13. [【Linux常用命令系列】linux echo由来用法示例权威详解](https://zhuanlan.zhihu.com/p/666660402)
14. [【Linux常用命令系列】Linux ls由来示例用法权威详解](https://zhuanlan.zhihu.com/p/666661004)
15. [【Linux常用命令系列】Linux中的yum命令 - 速查表](https://zhuanlan.zhihu.com/p/695991734)
16. [【Linux常用命令系列】Linux包管理： RPM（RPM软件包管理器）](https://zhuanlan.zhihu.com/p/696001489)
17. [【Linux常用命令系列】PING](https://zhuanlan.zhihu.com/p/696002559)
18. [【Linux常用命令系列】systemctl 手册](https://zhuanlan.zhihu.com/p/696010838)
19. [【Linux常用命令系列】LESS手册](https://zhuanlan.zhihu.com/p/696026369)
20. [【Linux常用命令系列】cat 手册](https://zhuanlan.zhihu.com/p/696028958)
21. [【Linux常用命令系列】route 手册](https://zhuanlan.zhihu.com/p/696071847)
22. [【Linux常用命令系列】ifconfig 手册](https://zhuanlan.zhihu.com/p/696090383)
23. [【Linux常用命令系列】ip 手册](https://zhuanlan.zhihu.com/p/696089843)
24. [【Linux常用命令系列】FIND  常用命令手册](https://zhuanlan.zhihu.com/p/708041770)
25. [【Linux常用命令系列】 ln](https://zhuanlan.zhihu.com/p/711835949)
26. [【Linux常用命令系列】PASSWD用户命令](https://zhuanlan.zhihu.com/p/711836515)



 
![img](https://pic3.zhimg.com/80/v2-92b4c936fadf5d184ca3d659fa161010_720w.webp)

## [SparkML：linux test由来示例用法权威详解](https://zhuanlan.zhihu.com/p/666662935/)

*源自专栏《[SparkML：大数据运维之常用linux命令系列目录](https://zhuanlan.zhihu.com/p/690059861/)》*

## **test — Linux 手册**

**名称**

test - 测试**文件类型**和**比较值**

## **描述**

test 命令用于测试[表达式](https://zhida.zhihu.com/search?q=表达式&zhida_source=entity&is_preview=1)的真假，并根据结果返回退出状态码。它通常用于[条件判断](https://zhida.zhihu.com/search?q=条件判断&zhida_source=entity&is_preview=1)和文件类型检查。

test 是一个常见的 shell 内置命令，最早出现在 Unix 系统中。它是许多 shell 脚本和[编程语言](https://zhida.zhihu.com/search?q=编程语言&zhida_source=entity&is_preview=1)中用于条件判断的基本工具。

## **选项**

适用于 test 命令的主要选项有：

| 选项 | 描述                     |
| ---- | ------------------------ |
| -b   | 文件存在且为块设备文件   |
| -c   | 文件存在且为字符设备文件 |
| -d   | 文件存在且为目录         |
| -f   | 文件存在且为普通文件     |
| -r   | 文件存在且可读           |
| -w   | 文件存在且可写           |
| -x   | 文件存在且可执行         |
| -s   | 文件存在且大小非零       |
| -e   | 文件存在                 |

## **十种主要用法及其代码示例**

以下是 test 命令的十种常见用法及相应的代码示例：

### 1.检查文件是否存在：

```text
test -e filename
```

### 2.检查文件是否为目录：

```text
test -d dirname
```

### 3.检查文件是否为空：

```text
test -s filename
```

### 4.检查**字符串是否为空**：

```text
test -z "$string"
```

### 5.检查两个值是否相等：

```text
test "$var1" = "$var2"
```

### 6.检查数值是否大于某个值：

```text
test $num -gt 10
```

### 7.检查文件是否可读：

```text
test -r filename
```

### 8.检查文件是否可写：

```text
test -w filename
```

### 9.检查文件是否可执行：

```text
test -x filename
```

### 10.检查文件是否是块设备文件：

```text
test -b filename
```

## **其他类似接口**

- [：[ 是 test 命令的等效形式，常用于**条件判断**和**条件语句**中。

## **详细区别**

test 和 [ 是等效的命令，它们的功能和使用方式完全相同。只是 [ 命令需要在表达式两端加上空格，并以 ] 结尾。这样设计是为了兼容早期的 shell 实现，因为 [ 是一个普通的命令，而不是关键字。

## **官方链接**

[test 官方文档](https://link.zhihu.com/?target=https%3A//www.gnu.org/software/coreutils/manual/html_node/test-invocation.html)


