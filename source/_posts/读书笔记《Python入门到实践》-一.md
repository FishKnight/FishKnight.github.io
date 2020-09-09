---
title: 读书笔记《Python入门到实践》(一)
date: 2020-09-07 19:06:53
tags: python
---
# 一.前言
+ **废话，自己给自己看的**
+ 最近几个月零散时间安排学习C++ primer plus和小灰大佬的《漫画算法》，前者阅读量大概在15%，后者阅读量大概在40%，现在突然想学Python（之前零零散散学习过一点点，感觉没啥用），明知今天一个目标明天一个目标是非常不明智的（聚集焦点完成一个目标然后再开始下一个目标，个人觉得是最值得推荐的），但是兴致来了，克制不了啊。尽然如此，那就找个亲和的资料（以前存的）学习学习咯。最终选择了《Python从入门到实践》，通过以白话的方式，力求以简洁记录该系列文章;
+ **目标**
    + *掌握Python语法*
    + 学会*自制开源Demo*
    + *教*小白入门python

# 二.初步认识
+ 不用了解太多，主要先从三个方面入手。其一,要知道学这个能做啥;其二,需要啥工具（环境）;其三,具体要先学些啥;
+ 1.python能用于众多方面：游戏，web应用，处理商业问题（暂时不用细化）,制作工具等;
+ 2.环境搭建-安装python3和文本文件（建议安装geany）
    + python3：系统已经安装好（我的电脑是[manjaro]Linux系统，所以只记录Linux相关的）;
    + geany:（控制台，通过Ctrl+Alt + T打开）执行命令（不同发行版命令不同，请自行查询），sudo pacman -S geany;
    + 刚接触编程，环境这块一定会碰到很多问题，这都是学习过程中必须经历的。由于环境方面的问题会有很多，如果碰到请及时查询资料或请教他人。
    + 记录一下在安装和配置geany的时候出现的问题

```python
1.安装问题：使用命令的时候报错，
错误：无法从 mirrors.sjtug.sjtu.edu.cn : The requested URL returned error: 404 获取文件 'geany-1.36-1-x86_64.pkg.tar.xz'
执行命令：sudo pacman -Sy，完成后继续执行刚刚的安装命令。
2.配置geany（存在多个python版本的情况下，必须要配置），具体请参考[Geany中配置python的方法](https://www.cnblogs.com/xtmp/p/11714520.html)
```

+ **配置geany的首选项**问题(比较棘手的问题，核心：xfce4-terminal)

  + [参考-manjaro gnome版本ctrl+alt+t怎么不能呼出terminal啊？](https://tieba.baidu.com/p/5053219568?red_tag=3046747515)
  + [记录一下-首选项的虚拟终端应该是什么](https://tieba.baidu.com/p/5785219444)
  + [centos7安装geany的一些配置](https://www.cnblogs.com/EdmundWong/p/8612167.html)

  ```python
  设置-键盘-应用程序快捷键-
  添加
  快捷键： Ctrl+Alt+T
  命令：xfce4-terminal --drop-down
  ```

  

