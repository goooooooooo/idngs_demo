---
layout: post
title:  "iDngs Website blog"
date:   2016-12-06
excerpt: "这是iDngs的Github Project介绍页面。"
project: true
tag:
- iDngs
- blog
- about
comments: true
---

![iDngs Homepage](http://www.xinyaaa.com/assets/images/20161209162030.jpg)    
    
<center><b></b></center>
     
本博客站点托管于Github上，属于静态博客。页脚信息有需要请自己添加。喜欢的话可以点击下方 ***Star*** 开始建设自己的博客站点。

<iframe src="https://ghbtns.com/github-btn.html?user=goooooooooo&repo=iDngs_demo&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>    
      
## git clone至本地预览

```
* 终端执行 'git clone https://github.com/goooooooooo/idngs_demo.git' 至本地文件
* 编辑本地目录中的 `_config.yml` 文件.
* 删除 `_posts` 文件夹中所有文件，然后写入自己文章。
* 删除 `site` 文件夹。
* 编辑以下目录中的文件替换成自己名字。
     目录中的 `index.md` 
     目录文件夹 `about` 中的 `index.md` 

修改完成执行 jekyll server 启动服务

浏览器访问http://localhost:4000 or http://127.0.0.1:4000 预览效果。
```  


## 预览效果

{% capture images %}
	https://cloud.githubusercontent.com/assets/754514/14509716/61ac6c8e-01d6-11e6-879f-8308883de790.png
	https://cloud.githubusercontent.com/assets/754514/14509717/61ad05ae-01d6-11e6-85ae-5a817dd8763b.png
	https://cloud.githubusercontent.com/assets/754514/14509714/61a89708-01d6-11e6-8fcd-74b002a060df.png
{% endcapture %}
{% include gallery images=images caption="预览效果截图" cols=3 %}

---

## 给萌新的说明区

检查目录全部文件确保jekyll能正确编译和运行。  

### 配置文件
`_config.yml` 是配置文件，站点所有配置都在这里面。

#### title

标题

例如： `title: My  Site`

#### bio

首页描述

#### description

标签和导航栏的描述

#### url

用于规范URL链接。

例如:

{% highlight yaml %}
url: http://www.idngs.com/idngs_demo
url: http://localhost:4000
url: //goooooooooo.github.io
url:
{% endhighlight %}

#### reading_time

'words_per_minute' 设为 'true' 时，文章中显示阅读时间，默认200秒。

#### logo
网站LOGO

#### background
背景，不懂请前往[W3CSCHOOL](http://www.w3school.com.cn/html/html_backgrounds.asp) 深⬆入⬆学习。⬅_⬅

#### 百度站长及工具

站长工具 的验证都能在 `_config.yml` 配置文件中写入. 获取更多meta标签信息请前往[百度站长平台](http://zhanzhang.baidu.com/college/courseinfo?id=267) 或 [Google Webmaster Tools](http://support.google.com/webmasters/bin/answer.py?hl=en&answer=35179) 获取更多支持.

#### MathJax
默认开启，不想用，在 `_config.yml` 设置中参数设为 'false'

---

### 导航链接

导航链接的设置，在目录 '_data' 中的 `navigation.yml` 文件。如下：

{% highlight yaml %}
- title: Home
  url: /

- title: Blog
  url: /blog/

- title: Projects
  url: /projects/

- title: About
  url: /about/

- title: iDngs
  url: http://iDngs.com/idngs_demo
{% endhighlight %}

