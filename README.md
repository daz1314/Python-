# Python-for-data-analysis-and-showing
Python数据分析与展示
一、 Anaconda IDE的使用
1.1 Anaconda
Anaconda集成各类python工具包，开源免费，有800多个第三方库，适合数据计算领域的开发

1.2 conda
conda是一个工具，用于包管理和环境管理。
其中包管理于pip类似，管理python第三方库，环境管理能够允许用户使用不同版本的python并且灵活切换。 
因此可以将anaconda视为一个集合，包含conda、某个版本的python以及一大批第三方库。 
而conda将工具、python、第三方库和conda自己都当做包，同等对待。
在Windows平台，进入cmd,进入conda存储路径，执行conda --version，查看当前版本； 执行conda update conda升级conda

1.3 编程工具Spyder
Spyder是anaconda自带的编程工具，下载anaconda后在开始菜单可以找到并打开

1.4 交互式编程环境 IPython
IPython是一个功能强大的交互式shell，适合进行交互式可视化和GUI相关应用。

IPython 变量前或后面增加？可以显示一些通用的信息，包括函数对应的源代码。

常用命令： %run demo.py 用于运行.py程序，
%run 在一个空的命名空间执行
% %magic：显示所有的魔术命令
%hist：IPython命令的输入历史
%pdb：异常发生后自动进入调试器 
%reset：删除当前命名空间中的全部变量或者名称
%who：显示当前命名空间中已经定义的变量 
%time statement：给出代码的执行时间，statement表示一段代码 
%timeit statement：多次执行代码，计算综合平均执行时间
