---
title: Hexo Blog
date: 2017-06-02 15:21:28
tags: hexo
---

I have created a new blog using [hexo](https://hexo.io/). Setup was very simple and I hope to continue using it to blog more.

{% codeblock [hexo setup] [lang:shell] %}
npm install -g hexo-cli
hexo init blog
cd blog
hexo server
{% codeblock %}

Once you are done you can create a git repo, add any customizations and commit.

{% codeblock [git init] [lang:shell] %}
git init
git add .
git commit -m "initial commit"
{% codeblock %}
