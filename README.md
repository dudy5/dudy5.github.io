# dudy5.github.io

发布博客：hexo clean => hexo deploy

新建文章：hexo new [layout] <title>，也可以直接在_drafts或_posts直接新建文件

本地访问：hexo server

配置域名解析：https://rainbomsea.xyz/2018/10/06/自定义博客域名/

如果你设置了自己的域名，就不能通过dudy5.github.io访问

*将多说duoshuo.js本地化：*

https://beeant0512.github.io/2016/03/21/duoshuo-embed-1458569563555/index.html

原始判断代码：ds.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') + '//static.duoshuo.com/embed.js';

*本博客用的valine评论插卡*
添加评论教程：https://www.jianshu.com/p/938fc79c7371

# 修改记录

1. 20191222 将duoshuo.swig全部代码使用{# #}语法注释

# 目录说明

_config.yml	配置文件

public	生成的静态文件，这个目录最终会发布到服务器

scaffolds	一些通用的markdown模板

source	编写的markdown文件，_drafts草稿文件，_posts发布的文章

themes	博客的模板
