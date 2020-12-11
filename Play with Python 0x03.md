# How to install Python ——Python的安装

安装Python非常简单，甚至MacOS自带Python2.7，如果你是Linux用户的话，部分Linux的发行版都自带Python2.7，并且默认的`python`命令调用的也是2.7

在[Python的官网](https://www.python.org/)可以下载到Python的所有版本。

<font color="red">**警告：不要再百度之类的搜索引擎提供的不正确的链接下载任何东西，请务必在Python官网下载**</font>

任何非官网下载的Python版本都有内容不全，或者被修改，或者带有病毒的风险，请移步Python官网下载

（上面的蓝色字体的Python的官网可以打开Python官网，亦可采用此链接https://www.python.org/）

值得注意的是，Python的官网的[download](https://www.python.org/downloads/)页面有有一个信息<font color="#66ccff">**Active Python Releases**</font>

这里可以看到现下主流的Python版本，包括一些其他版本的保养状态，也就是生命的尽头

比如2020/7/30这一天，Python2.7的保养状态就是` end-of-life`

#### Windows

windows用户只需要下载Python官网提供的exe版本，然后安装，值得注意的是，安装时有一个`Add to path`的选项，记得勾选即可



#### Linux用户

Linux用户可以考虑`apt-get`之类的方法安装

但是不是所有的Linux都支持`apt`，所以这里讲如何编译源代码

linux一般都自带gcc，只要有这个问题就不大

下载Python的源代码，解压，然后terminal进入解压后的目录

依次输入

`./configure`

`make install ./`



