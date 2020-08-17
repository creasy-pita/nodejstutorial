# nodejs tutorial home

## nodejs module  模块

### 模块加载机制练习

目录： module/manage
运行：node .\module\manage\test.js

#### nodejs运行和打包区别

运行是直接当前的模块文件编译运行，不组成新的模块
打包是把当前的模块文件组块成一个新的模块供其他模块去使用

共同点：都又入口文件，然后去解析模块键的依赖，建立模块依赖树等动作
不同点：运行一般会在入口文件，结合使用其他模块的功能，输出结构，比如这里的.\module\manage\test.js的 console.log(a.a);

#### C/C++ 扩展模块的开发以及应用场景

##### 好处

像c#可以加入c++的内建模块的调用，提高底层对操作系统的处理能力
nodejs是单线程，可以使用c++扩展模块，加入多线程的功能

##### 扩展方式

##### 扩展参考

[C++ Addons nodejs.org](https://nodejs.org/docs/latest-v6.x/api/addons.html )
[扩展模块的开发以及应用场景]( https://zhuanlan.zhihu.com/p/35238127)

### 参考

[Module 模块机制](https://www.bookstack.cn/read/Nodejs-Roadmap/nodejs-module.md)
[结合源码分析 Node.js 模块加载与运行原理](https://zhuanlan.zhihu.com/p/35238127)
