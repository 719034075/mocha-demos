这份demo是fork阮一峰老师的**mocha-demos**示例库。

[原库地址](https://github.com/ruanyf/mocha-demos)

[测试框架 Mocha 实例教程](http://www.ruanyifeng.com/blog/2015/12/a-mocha-tutorial-of-examples.html)

在阮老师的demo基础上，做一些关于我自己学习`Mocha`的笔记

***

> Mocha的作用就是运行测试脚本。

我在本地安装`mocha`和`mochawesome`之后运行

```cmd
>..\node_modules\.bin\mocha add.js --reporter -mochawesome
```

会报错
```cmd
"-mochawesome" reporter not found
```

但是安装在全局之后就正常生成报告了。。。原因不详，似乎跟目录切换有关。

