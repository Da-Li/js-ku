---
layout: detail_tmp
title: js-ku协作开发文档
intro: 包含GitHub 基本操作。
categories: test
keyword: js-ku协作开发，github 教程，jekyll教程
author: li
show_type: image
show_intro: /res/img/page/test/open-source.jpg
---

# js-ku协作开发文档

--- 

## GitHub 与 Jekyll

![jekyll和github教程](/res/img/page/test/open-source.jpg) 



1.下载Rubyisntallers[downloads](http://rubyinstaller.org/downloads/) 一路下一步。

2.下载`Devkit` 就在下载`Ruby`的下面。完成后解压。注意和Ruby版本一致。

3.用`cmd` cd 到 Devkit 目录，运行。
    
    ruby dk.rb init 

4.修改`config.yml` 根据示例，添加`Ruby` 和 `Devkit`的路径。

5.执行
    
    ruby dk.rb install

6.安装 Jekyll(后续，安装Jeykyll 问题汇总。)
    
    gem install jekyll

7.下载完成.我们可以cd 到从Github clone 下来的项目。

    jekyll serve

>Jekyll 默认监控4000端口。所以我们访问 127.0..0.1:4000 就可以了。

![jekyll和github教程](/res/img/page/test/fork.png) 
如果喜欢，可以点*start* 



2.clone 项目到本地。 



3.`xxx.md`的配置 

&nbsp;&nbsp;3.1 categories *_posts* 下的文件夹/分类 

&nbsp;&nbsp;3.2 show_type 列表展示的类别。[image,slider,video]

&nbsp;&nbsp;3.3 show_intro 根据 `show_type`。如果show_type: image 则 show_intro： 就是图片链接地址（相对路径）;

&nbsp;&nbsp;3.3 intro 简述。

&nbsp;&nbsp;3.4 title 标题
 
&nbsp;&nbsp;3.5 author 作者
 
&nbsp;&nbsp;3.6 keyword 页面关键词
 
&nbsp;&nbsp;3.6 layout 选择模板（detail_tmp）

4.[markdown](http://lixiaoshenxian.com/markdown.html) 写作方式 

------------------ 
#注意事项 

`show_type `与 `show_intro` 对照关系。 


| show_type ||||      show_intro      |
|-----------||----------- |
| image||||图片路径（相对）| 
| slider||||轮播图，图片路径（相对）用 ';'分开|
| video||||暂不支持|

------

>其他未尽事宜 联系 qq 1010420114

