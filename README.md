# 快速搭建Visual Studio Code的C/C++开发环境
## 环境搭建
1.下载安装[Visual Studio Code](https://code.visualstudio.com/download)<br/>
2.安装[MinGW64编译器](https://sourceforge.net/projects/mingw-w64/)。如果已经有Dev-c++，则MinGW64在Dev-Cpp\MinGW64\下<br/>
3.安装C/C++插件：在扩展中搜索“C/C++”，安装插件<br/>
4.下载releases的zip文件，解压后运行.exe文件，输入vscode工作区路径和编译器MinGW64的路径并确认<br/>
5.在vscode中打开工作区，新建cpp文件，写好代码后即可调试运行
## 注意
1.源文件(.cpp)默认的文件编码是GBK，这样可以解决控制台输出中文有乱码的问题<br/>
2.源文件(.cpp)编译出来的可执行文件(.exe)是工作区的.exe文件夹下的a.exe，所以源文件的文件名可以含中文，但不能正常调试。若想调试，请把源文件的文件名改为不含中文的文件名。
