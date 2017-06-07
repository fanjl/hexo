---
title: hexo分类与tags的配置
tags: [hexo,tags,cagegories]
date: 2017年06月07日 09时48分30秒
grammar_cjkRuby: true
---
# <h2>添加分类<h2>
命令提示符进入hexo目录
hexo new page categories
确认站点配置文件里有category_dir: categories
确认主题配置文件里有categories: /categories
编辑站点的source/categories/index.md，添加以下代码：

``` stylus
---
title: categories
date: 2017-06-07 09:33:49
type: "categories"
comments: false
---
```
<!--more-->
# <h2>添加标签<h2>
hexo new page tags
确认站点配置文件里有tag_dir: tags
确认主题配置文件里有tags: /tags
编辑站点的source/tags/index.md，添加以下代码：

``` stylus
title: tags
date: 2017-06-07 09:34:22
type: "tags"
comments: false
```
编辑文章时，tags按照以下格式写：

``` stylus
tags: [tag1,tag2,tag3]
```
需要注意的是，tags后面要有空格。




