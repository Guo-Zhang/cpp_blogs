# Python安装与环境配置

<!--
本文以后作为开课的前置教程使用
-->

- 作者：张果、xxx。
- 创建时间：2017-07-07
- 修改时间：2017-07-07


## Python安装

### Python

打开[Python官网](https://www.jetbrains.com/pycharm/)，安装3.6.1，也可以同时安装2.7.13。

### pip

在Win CMD或者Unix Shell输入
```
pip install requests
```
检查pip命令是不是正常。注意，如果同时安装了2和3，请使用pip2和pip3，此时pip可能会是你最后安装的Python版本。

这里有几个坑，写文章的CPPer注意详细解释（作为文章的亮点）：
- pip命令在Win下会怎么命名？是pip2还是pip2.7还是pip，还是会冲突？
- Win的2.7版本安装包有时候会没有pip命令，是什么原因？怎么补装pip和easy_install?

## Pycharm
- https://www.jetbrains.com/pycharm/
- 可以安装社区版，也可以注册学生账号安装专业版。
- 注意，在注册的时候有一步需要google服务，所以必须翻墙完成。


## Jupyter
- 安装Jupyter：http://jupyter.org/install.html，以pip的形式安装。
- 安装完成以后按以下步骤测试：https://jupyter.readthedocs.io/en/latest/running.html#running。
