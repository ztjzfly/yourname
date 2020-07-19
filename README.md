本项目为GitHub Pages 博客模板，目标是尽可能使用网页操作完成个人博客从创建到发布的全过程。

# 创建阶段
- 申请您自己的 GitHub 帐号。
- Fork 这个项目到您自己的 GitHub 帐号下，命名为 `yourname.github.io` （yourname替换成您自己的 GitHub 账户名）。
- 根据[此页面](https://hexo.io/zh-cn/docs/github-pages)的指引配置 Travis CI。
- 若您使用自定义域名，请务必编辑 `./public/CNAME` 文件，写入您的自定义域名；若您使用默认的 GitHub Pages 地址请务必清空或删除此文件。
- 访问您的自定义域名 (https://yourname.yourname.com) （或 (https://yourname.github.io) )。
- You Got It!

# 个性化
- 一些基本配置在 `./config.yml` 中。
- 本项目使用 yilia 主题，还有些主题级别的配置在 `./themes/yilia/config.yml` 文件里。
- 关于贴文地址的生成规则详细说明请参照 Hexo 管方文档[永久链接（Permalinks）](https://hexo.io/zh-cn/docs/permalinks)一节，本项目默认配置为 `:title/` 样式（ title 包含文件夹层次），您也可以根据需要修改此参数。

# 发布文章
- 贴文放在 `./source/_posts` 目录下，可套多层文件夹来方便分类管理贴文。
- 贴文元数据字段说明：
```
title:	标题
date:	日期，格式为 2020-02-02
categories: 分类（可用做合集）
tags:
- 标签1
- 标签2
- 可以加很多很多标签
---

正文兼摘要
剩余正文。

正文里空多行展示效果也只是空一行。

想空多行的话要增加换行标志 `</br>` 。
```