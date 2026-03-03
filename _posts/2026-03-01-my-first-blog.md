---
layout: post
title: My first blog
subtitle: There's lots to learn!
gh-repo: hsjy/bj.github.io
gh-badge: [star, fork, follow]
tags: [test]
comments: true
mathjax: true
author: hs
---

{: .box-success}
Hello, [World](http://www.baidu.com/)! <br/> I'm pretty glad to be here.

[GitHub Pages](https://docs.github.com/zh/pages/getting-started-with-github-pages/what-is-github-pages) 是一项静态站点托管服务，它直接从 GitHub 上的存储库获取 HTML、CSS 和 JavaScript 文件，（可选）通过构建过程运行文件，然后发布网站。

GitHub Pages 会发布您推送到仓库的任何静态文件。 您可以创建自己的静态文件或使用静态站点生成器为您构建站点。 您还可以在本地或其他服务器上自定义自己的构建过程。

我的思路就是本地构建静态网站（Jekyll）并预览，调试成功再交由github page。

主题选择： **[beautiful-jekyll](https://github.com/daattali/beautiful-jekyll)**
首先fork到本账号下的仓库，接着将项目克隆到本地，本地安装Ruby环境，安装 Jekyll 和 Bundler，安装项目依赖，启动本地服务器预览。在本地调试成功后通过git管理上传到仓库，从而启用github page的功能。
安装Ruby环境(windows)：
安装RubyInstaller： https://rubyinstaller.org/
下载带Devkit的版本，勾选运行msys2安装必要的编译工具链。
gem和bundle切换国内清华源： https://mirrors.tuna.tsinghua.edu.cn/help/rubygems/
安装Jekyll和Bundler:
`gem install jekyll bundler`
gem相当于python中的pip
安装项目依赖：
`bundle install`
该行命令相当于安装requirements.txt解决依赖问题
启动本地服务：
`bundle exec jekyll serve --livereload`
一切顺利的话可以到 http://127.0.0.1:4000 访问本地网站了。

![Crepe]({{ '/assets/img/path.jpg' | relative_url }})

ok本地在\_page下按照时间创建页面后仿照模版的指示创作（First blog），注意在hs分支上做，本地预览（除了\_config不会热更新，其他的改动基本会Regenerating），差不多可以之后就通过git管理add commit push 上传到github上，同时修改github项目的Page页设置，使hs分支作为展示页，**等待1/2分钟**，重新加载github网址，成功。

{: .box-note}
**Note page:** github page的网址： https://hsjy.github.io/bj.github.io/

<details markdown="1">
<summary>Click here!</summary>
Here you can see an **expandable** section
</details>
