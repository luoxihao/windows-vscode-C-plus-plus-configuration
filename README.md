# windows-C-plus-plus-configuration
#配置方法在这里！！！！

先下载个vscode ：https://code.visualstudio.com/

minGW下载地址：

链接：https://pan.baidu.com/s/1gBaiUI-ITIquNe7-oP7Jaw

提取码：r4r0

下载minGW后把它随便放在一个文件夹中，再去配置环境变量：可以百度一下
```
1.右键此电脑 点击“属性” 点击“高级系统设置”（在左边）

2.点击“环境变量”

3.下方有个系统变量的框 在里面找到Path 双击Path

4.点击新建 键入minGW的路径到这里  路径一定要到bin 例子：G:\MinGW64\bin
```
新建一个文件夹 右键用vscode打开（可以把这个文件夹命名为vscode）

在这个文件夹中再新建一个文件夹名为.vscode，  再把从github上下载的四个配置文件放到.vscode里面 

这四个配置文件里面有注释 说明了要改路径的地方 修改到你自己的路径即可

在自己建的vscode文件内创建一个cpp文件 cout或者print个hello world F5调试 

输出hello world 

配置完成
