---
layout:     post
title:      Hello My First Blog
subtitle:    "\"Hello World, Hello Blog\""
date:       2019-05-30
author:     Ethan
header-img: img/post-bg-2015.jpg
catalog: true
tags:
    - Blog
---

> “🙉🙉🙉 ”


## 前言

Ethan的 Blog 就这么开通了。

开博客其实是很早就像做的一件事情，但是国内的 CSDN 之类的....糟糕的页面设计和低下的设置灵活度，总是让人望而止步。

在自己等丹炉训练结果的时候，突然逛到了一个国外大神在 GitHub 上开设的博客，于是想起自己很早的愿望。于是开始动手在自己的GitHub账号上建立博客。终于，在 [BY BLOG](https://qiubaiying.github.io) 的帮助下（手动点赞:+1:），成功利用模板（尽管还不知道内部原理:joy:)总算开通 ~~套出~~ 自己的博客。

This is Ethan's first blog，enjoy it ! :laughing:

<p id = "build"></p>
---

## 正文

接下来说说搭建这个博客的技术细节（虽然并不都是自己做的:joy:）。  

整个博客都是依赖于 [GitHub Pages](https://pages.github.com/) + [Jekyll](http://jekyllrb.com/) 快速 Building Blog 的技术方案，非常轻松时尚。

其优点非常明显：

* **Markdown** 带来的优雅写作体验（与本地的 **Typora** 配合起来更是天作之合）
* 非常熟悉的 **Git workflow** ，**Git Commit 即 Blog Post**(所有的变化都是直接先在本地做出更改，然后远程提交)
* 利用 GitHub Pages 的域名和免费无限空间，不用考虑物理主机的问题
	* 可能等以后有时间的话，自己折腾一下自己的 **Blog** 域名。
* Jekyll 的自定制非常容易，基本就是个模版引擎



---


主题主要依赖于 [Hux的博客主题](https://huangxuan.me/) 。

而本地调试环境（这个我还没时间配:tired_face:，先抄下来以作日后参考）需要 `gem install jekyll`，结果 rubygem 的源居然被墙了，~~后来手动改成了我大淘宝的镜像源才成功~~，淘宝的源已经[停止维护](https://gems.ruby-china.org/)，换成了OSChina的源 `https://gems.ruby-china.org/`。


## 后记

最后，感谢 Hux 提供的的 [Blog 主题](https://github.com/Huxpro/huxpro.github.io)

如果你恰好逛到了这里，希望你也能喜欢这个博客主题，感兴趣的话可以自己动手搭建一个。

—— Ethan 后记于 2019.5.30


