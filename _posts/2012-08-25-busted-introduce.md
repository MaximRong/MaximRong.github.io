---
　　layout: default
　　title: 你好，世界
---

busted
==========

busted 是什么?
-------------------------
busted is a unit testing framework with a focus on being easy to use. busted works with lua >= 5.1, moonscript, and LuaJIT >= 2.0.0

busted是一个单元测试框架，他的特点是简单易用(对于没用过lua的人来说 还是有点麻烦的)，busted工作需求lua >= 5.1 , moonscript, 和 LuaJIT >= 2.0.0

如何安装busted
-------------------------
要运行busted，最好使用Linux环境，因为在windows环境下操作busted非常麻烦，其所需要的安装环境等等都不大兼容window(虽然可以使用cygwin,但支持的还是非常不好), 所以本文也是介绍如何在Linux下使用busted。

1.  要安装busted，第一步，要知道一个东西 ： Luarocks！！ 这是什么呢？ Luarocks说白了就是lua生态环境中的Maven，负责统一管理第三方扩展功能包的。而busted就是通过Luarocks来安装的。

