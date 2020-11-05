# miniplc0-java

这里是 miniplc0 实验的 Java 版本。

编译原理第二次实验作业。

### 编译原理作业总目录
https://github.com/ZhuChenyuCZ/CompilerHomeWorkList

### 如果我的作业对你有帮助的话，麻烦给个star吧：D

## 语法分析作业

### ⚠️注意

本作业是java版本的miniplc0-java编译器

forked from [BUAA-SE-Compiling/miniplc0-java](https://github.com/BUAA-SE-Compiling/miniplc0-java)

### 作业文档

作业发布贴

http://forum.loheagn.com/d/126-miniplc0

评测入口

https://oj.karenia.cc/suite/1frfy6wdjce1a

miniplc0 实验指导书

https://github.com/BUAA-SE-Compiling/miniplc0-handbook

Miniplc0 Java 版指导书

https://github.com/BUAA-SE-Compiling/miniplc0-handbook/blob/master/readme-java.md

Miniplc0 C++ 版指导书

https://github.com/BUAA-SE-Compiling/miniplc0-handbook/blob/master/readme-cpp.md

miniplc0 虚拟机标准

https://vm.buaasecompiling.cn/

### 快速开始

#### 本地方法

clone该仓库后，在miniplc0-java文件夹的目录下创建in.txt和out.txt两个文件。

in.txt中是需要被编译的程序。

out.txt中是编译的结果。

在命令行中输入

```bash
//需要安装gradle
gradle fatjar
//词法分析测试
java -jar ./build/libs/miniplc0java.jar -t -o out.txt in.txt
//语法分析测试
java -jar ./build/libs/miniplc0java.jar -l -o out.txt in.txt
```

#### OJ测试方法

在评测机中输入仓库地址以及分支名称，点击提交。

### 其他相关地址

测试OJ Rurikawa

[https://oj.karenia.cc](https://oj.karenia.cc/)

SystemProgramming 论坛

[http://forum.loheagn.com](http://forum.loheagn.com/)

评测机开源仓库

https://github.com/BUAA-SE-Compiling/rurikawa

评测机使用说明

https://github.com/BUAA-SE-Compiling/rurikawa/blob/master/docs/manual/submit.md
