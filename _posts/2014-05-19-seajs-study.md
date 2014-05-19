---
layout: post
title: seajs 学习笔记
---

# seajs 学习笔记

## 为什么要使用
首先javascript是一个设计很糟糕的语言，它不是为了制作大型程序而开发的一种语言，一开始的时候javascript只适合作一些小型的开发，随着ajax,html5的兴起javascript不断在扩大着自己的应用领域．

当程序不断增长以后，就需要对程序划分模块，模块之间相互依赖调用，但是javascript语言当前还没有这样的功能，所以这就催生了很多第三方的模块管理加载库

## 遇到的问题
在我使用的过程当中，遇当css文件的问题
当require("abc.css")
以css方扩展名的文件，在用spm build构建后，在生成的文件中，没有将css文件添加到依赖列表中，导致构建后的文件无法加载css文件

处理办法可以修改 abc.css文件名为abc-css

## 还需要继续学习的问题有

   - spm package.json格式问题
   - seajs模块的规则还不是很熟悉
   - javascript变量作用域问题
     
        [深入理解javascript变量的作用域](www.cnblogs.com/rainman/archive/2009/04/28/1445687.html)
   - markdown语法规则
        
        [学习使用markdown语法](http://wowubuntu.com/markdown/)

