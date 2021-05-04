# Python3的介绍＋入门--第三讲：变量，错误

> Python 中每个变量在使用前都必须赋值，变量赋值以后该变量才会被创建。

在 Python 中，变量就是变量。

等号（=）用来给变量赋值。

等号（=）运算符左边是一个变量名,等号（=）运算符右边是存储在变量中的值。例如：
```python
	name = "jonathanqwq"   # 字符串
	print(name)
```
执行以上程序会输出如下结果：
```控制台
	jonathanqwq
```
### 多个变量赋值

Python允许你同时为多个变量赋值。例如：
```python
	python
	a = b = c = "1"
```
以上实例，创建一个字符串对象，值为 1，从后向前赋值，三个变量被赋予相同的数值。

# 错误

> 在程序执行过程中发生的任何错误都是异常。每个异常显示一些相关的错误信息。

### SyntaxError（语法错误）
你在 Python3 中使用 Python2 独有的语法就会发生 SyntaxError（语法错误）

### IndentationError（缩进错误）
不小心在行首多打了一个空格就会产生 IndentationError（缩进错误）

### NameError（名称错误）  
当访问一个未定义的变量则会发生 NameError（名称错误）。  
NameError: name 'jonathanqwq' is not defined
最后一行包含了错误的详细信息，其余行显示它是如何发生（或什么引起该异常）的详细信息。

### TypeError（类型错误）
TypeError 也是一种经常出现的异常。当操作或函数应用于不适当类型的对象时引发，一个常见的例子是对整数和字符串做加法。
