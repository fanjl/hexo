---
title: hexo添加about页面 
tags: [hexo,about]
date: 2017年06月07日 10时14分17秒
grammar_cjkRuby: true
---
hexo添加about页面大致分两步，新建about页面和在菜单中添加链接
#<h2> 新建about页面<h2>
有两种方法：

 1. 在source文件夹下新建about文件夹，在about文件夹下新建index.md
 2. 使用 hexo new page "about" , 可以直接生成about.md
 编辑index.md文件，开头大致如下：
 

``` stylus
---
title: about
date: 2017-06-07 09:31:57
comments: false
---
```
<h2>在菜单中添加about链接<h2>
进入hexo所使用的主题目录，themes/<theme_name>/ 编辑_config.yml里面的menu一项，添加一行About: /about。
ok大功告成，剩下的就是自己在about页面里添加一些内容就可以了。

