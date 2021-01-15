#  String——字符串

<table><tr><td bgcolor=Black><font size=5 face="consolas" color=white><center>————————————————CopyRigth: Lingmux-2020————————————————</center></font></td></tr></table>



如果你还不知道什么叫做字符串，可以看看↓

### 什么叫字符串？

字符串，是由零个或多个字符组成的有限序列。一般记为。它是编程语言中表示文本的数据类型。

严谨的定义就是这样的，但是不好理解，加单来说就是一段文字

还记得我们在hello_world章节中写过的代码吗？

``````python
print("Hello World!")
``````

这里用**双引号**引起来的部分就是字符串

如果你已经阅读过本书的目录的话， 不难发现，在字符串章节，我设置了4个小的章节，其实只是对应了字符串的不同表示方法

#### “This is a string !”

正如题目中所描述的，用双引号引起来的部分，是一个字符串

你可以在IDLE/python模块中尝试以下代码

```python
foo = "this is a string"
print(foo)
```

当然，除了双引号以外，单引号也是可以的，

```python
foo = 'this is a string'
print(foo)
```
如果你写过C++，Java，C#等语言，应该会觉得奇怪，“单引号内的不应该是单个的字符吗？”
对，在大多数语言中，使用单引号来表达char类型，用双引号表达string类型或者是char array类型，但是python中，单引号引起来的也是字符串哦~

除此之外，Python还提供了三单引号，三双引号字符串，他们都是字符串，但是具体的区别，我们会在后续的章节中陆续的介绍；

### 字符串方法

什么叫做字符串方法？

如果你熟悉C语言，一定知道`strlen()`这一类的函数，可以对字符串进行不同的操作，比如求取长度，复制，对比两个字符串等，Python中，对字符串也有很好的支持，这里分以下几个模块进行介绍



##### 字符串的运算符



字符串支持`+`，`*`，`[]`等不同过的运算符

* `+` 拼接字符串
* `*` 重复字符串
* `[]`索引字符串（切片操作）
* `[:]` 截取一部分
* `in` 成员运算符，查看字符串是否含有某个特定字符
* `not in` 成员运算符，查看字符串中是否不包含某个特定字符串
*  `r/R` 将字符串进行转义

```Python
str_foo = "I am string Foo"
str_bar = "I am string Bar"

str_foobar = str_foo + str_bar # 字符串之间的加法，可以用于拼接两个字符串
print(str_foobar) # "I am string FooI am string Bar"
```

```python
foo = "abc"
print(foo * 3)# "abcabcabc"
```

```Python
foo = "Fox-Doty"
print(foo[0]) # "F" ，注意，计算机中的计数是从0开始的
```

```python
foo = "Fox-Doty"

print(foo[:3]) # "Fox"，截取从编号0到编号3（的前一个）的字符
```

```python
foo = "Fox-Doty"

print("Fox" in foo) # True
```
```python
foo = "Fox-Doty"

print("Bar" in foo) # True
```

在Windows系统中，`\n` 表示换行，比如

```python
foo = "abc\nbca"
```
在调用print函数打印foo的时候，在abc的尾巴会进行换行，然后bca在abc的下一行进行输出，但是有时候我们不希望这个反斜杠带有一些特殊的意思，比如我们希望
`'D:\new_project'`

我们希望上面这个字符串表示的是一个系统中的文件地址，而不是在`"D:"`后面换一行然后打印出`ew_project`，这种时候我们就可以在这个字符串前加上r或者R，表示【去除特殊含义】

```python
foo = "D:\new_project" # 小心换行！

bar = r"D:\new_project" # 单纯的表示一个地址
```
