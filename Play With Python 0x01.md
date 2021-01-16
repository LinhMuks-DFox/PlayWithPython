# Play With Python ！ 

Author： Lingmux 

Copyright: Lingmux 2020

Connect Me By [Gmail](muxxum65536@gmail.com)



如题所见，这是一个Python教程  

本教程旨在使用浅显易懂的语言表达，来讲述Python的强大。

## Before we start

开始论述Python的内容之前，我想简单的阐述一下我的学习心得。

不得不说，学习是一个枯燥乏味的过程，熟练的掌握某一门语言，意味着你需要不停地练习编码和不停地查阅资料。一件事情做一次会让人觉得兴奋，每天重复的做，就会让人厌恶。

学习编程的道路上总会遇到许多阻碍，看不懂的书，这样那样的晦涩难懂的专业术语，看不懂的代码，莫名其妙的错误和难以理解的思想。

初期阶段的枯燥乏味的过程和难以文档的文档和教程，是很多人放弃学习的最大的原因（至少作者认为）

确实，作者本人在学习编程的时候，也着实遇到了许多艰难险阻。

不过没关系，你发现了本教程。

本教程旨在使用简单易懂的方式来讲述复杂的内容，化繁为简，是一种强大的能力，在学习的道路上总会遇到这样那样的问题，许多坑已经被作者本人踩过了，本着自己才过的坑要填好的宗旨，我写下了这套教程。

另外，学习时不要过的追求完美

引用@liubobo老师举得一个例子，一本单词书，硬性地记忆每一章节的每一个单词并且不产生错误是不切实际的。正确地记单词应该是从头到尾地记忆一遍，然后再某个时间想不起来某个单词却又需要时，再回来查询，记忆

不然只拘泥于第一章，你将日夜地背诵abandon，直到你abandon这本书。

学习编程也是这样，从头到尾地看一遍教程，认真地记笔记，尝试敲代码，但是不要过分地要求完美，要求自己记忆每一个细节，在某些地方想不起来时，再回头查资料。

最后：**本教程基于Python3.x**

**Python2.x在2020年将迎来声明的尽头，2020年鼓吹Python2的人应该拉出去枪毙五分钟在拖回来宫刑**



## 目录



* What is Python? ——Python是什么？
* How to install Python ——Python的安装
    * Windows
    * Mac
    * Linux
* Write Hello world Program with Python ——用Python书写Hello World 
    * IDLE
    * Python File(.py) and Python Interpreter
* Basic Data Structure and Variable in Python   ——Python的基础数据结构以及变量
    * Numbers —— 数字
        * Integer ——整数
        * 进制转换
        * Float and Double ——浮点数
        * Decimal ——小数
        * Complex——复数
    * String——字符串
        * `“This is a string !”`
        * `‘This also a string!’`
        * `""" This also a string! """`
        * `'''This also a string'''`
    * Iterable types可迭代类型
        * Tuple ——元组
        * Set ——集合
        * List ——列表
        * Dictionary ——字典
    * Citation type and value type——引用类型和值类型
* Operator in Python ——Python中的运算符
    * 四则运算
    * 布尔运算
    * 为什么没有自增运算和自减运算？
* Indent in Python ——Python的缩进
* Process control ——Python的流程控制

    * if else elif ——如果……的话；还有，如果……的话；最后，都不行那就
    * for loop ——for循环
    * while loop ——while循环
* Import and Export ——导入导出

    * Package，class，variable ——包，类，变量的导入导出
    * About `__init__.py ` ——`__init__.py`的正确打开方式
* Method/Functions in Python ——函数

    * Method/Functions in Python ——Python中的函数
    * serial unpacking, chain assignment——序列解包，链式赋值
    * The Arguments of Python Methods—— Python函数的参数
    * Scopes of the variables——变量的作用域
    * Key Word `global`
* OOP in Python——Python的面向对象

    * 类与对象`(object)`
    * `class`关键字
    * Constructor ——构造函数
    * Class Variable, instance variables——类变量，实例变量
    * Instance Methods，class method，static Methods——实例方法，类方法，静态方法
    * Inheritance of classes ——继承
        * 单继承
        * 多继承
    * 成员的可见性
    * 关于面向对象的一些编码习惯
* Exceptions and Warnings ——错误与警告

    * What exactly are the errors and warnings? ——错误和警告具体是什么
    * How to define an error or warning？——如何定义一个错误或者警告
    * How to throw a warning or an error？——如何抛出一个警告或者错误
    * How to handle warnings or exceptions that can be expected？——如何处理可以预期的警告或者异常
* 进阶Python知识：

    * Python中的魔法方法
        * 重新回顾运算符
    * Context Manager——上下文管理器
        * `with`statement——`with`语句
        * Implementing a class that supports with statements——实现支持with语句的类
    * Iterator——迭代器
        * What is an Iterator——什么是迭代器
        * Implementing a class that can be iterated on——实现一个可迭代的类
    * Generator——生成器
    * Enum in Python ——Python的枚举
    * Lisp up! ——函数式编程
        * 匿名函数
        * 三元表达式
        * map
        * reduce
        * filter
    * Decorator——装饰器

    * Senior OOP——再回顾OOP，高级的面向对象
        * type()函数的高阶玩法
        * 元类型
    * 列表推导式&Pythonic
    * Regular expression——正则表达式
