#前提确保Visual Studio Build Tools 安装了VS2022编译工具包括如下两个组件：

C++的桌面开发：此工作负载包含了C++编译器、调试工具以及常用的C++库等，是编译Python C扩展所必需的。
Pthon开发：此工作负载包含了Python解释器、开发工具和常用的Python库等，是编译Python C扩展所必需的。 #官方版本pip install editdistance会出现报错
在构建 editdistance 库的 wheel 包时出现了编译错误，主要问题集中在 src/editdistance/_editdistance.cpp 文件里，存在语法错误 #解决方法
下载Release目录下editdistance-0.8.1.tar.gz文件
pip install ./editdistance-0.8.1.tar.gz 注意这个./表示当前目录下，如果不在当前目录下需要指定文件路径
