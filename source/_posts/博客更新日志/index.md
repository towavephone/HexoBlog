---
title: 博客主题更新日志
categories:
  - 博客主题
tags:
  - 主题优化
permalink: update
date: 2018-04-24 20:29:35
fancybox:
original:
comments:
toc_list_number: false
top: 1
---

# 前言

本篇日志用于记录博客主题的更新情况。

为方便编辑和查看最新进展，更新以时间倒序方式呈现。

<!--more-->

# 2021 年

## 12 月

### 19 日

- 网站迁移到 github，使用 github actions 自动部署

# 2018 年

## 5 月

### 6 日

- 技术内容迁移到新站点 http://blog.towavephone.com ，本博客以后只记录非技术内容

## 4 月

### 28 日

- 添加随机背景图片
- 将初始老婆换为`涅普顿`
- 更改主题配色

### 27 日

- 修复初次访问网站头像切换问题
- 优化移动端下的加载脚本：移动端不加载 live2d，PC 端不加载 slideout
- 修复文章原始链接不生效的问题
- 改变博客字体，增加行高

### 26 日

- 添加 live2d 头像，保留原来的头像，实现切换效果
- 修复谷歌浏览器下移动端侧边栏打开后背景透明问题
- 更换移动端侧边栏

### 25 日

- 更换网站头像为萌黑猫
- 添加代码复制功能

### 24 日

- 网站底部添加本站文章总数
- 优化 hexo，采用 fragment_cache 缓存优化生成网页时间，由原来的 2min 减少到 8s 左右

### 22 日

- 首页添加 `<meta name="renderer" content="webkit">` 请求头，以开启 360 极速模式。
- 解决 PC 端子类滚动引起父类滚动问题

### 20 日

- 阿里云备案成功，在博客底部添加 ICP 备案号
- 打开百度自动推动，百度统计，奇虎 360 自动推送功能

### 19 日

- 由于 gulp 中的 uglify 组件添加对 es6 的支持，故解决了升级 hexo-blog-encrypt 组件编译错误问题
- hexo-blog-encrypt 中添加加密文章解密后可以查看目录的功能。
- 删除 hexo-fs 组件，有了这个会报错，hexo 已含有这个组件。

### 18 日

- 修复 Ubuntu 上 hexo g 不能生成网页的错误，之前一直卡在这
- 更改 gitlab 部署脚本，博客迁移到阿里云服务器
- 升级 package.json 的各个组件

### 17 日

- 文章图片的最大高度由 250px 变为 300px

### 16 日

- 文章宽度由 80em 变为 75em

### 14 日

- 博客迁移到 gitlab 上，编写 gitlab 部署脚本，不再更新 github
- 删除 yelee 主题多余部分
- 去掉标签切换圆角效果
- 修复目录切换文字切换问题
- <s>升级 hexo-blog-encrypt 组件</s>，发现编译错误，已降级

### 9 日

- 修复移动端文章、gitalk 过于靠边 bug

### 8 日

- 修改 hexo-qiniu-sync 组件，为了 lazysizes 默认只加载图片的 data-src 属性
- 优化网站图片大小，采用七牛云压缩
- 关闭背景图随机切换，以提高加载速度
- 文章宽度由 70em 变为 80em
- 更改标签切换图标与主题风格一致
- 修复点击目录标题图标切换错误

### 7 日

- 优化 js 加载速度，尽量采用 defer，async 属性
- mathjax 修改为默认全局不加载，按文章需求加载
- 关闭 addthis 分享，提高加载速度
- 关闭谷歌、百度统计
- 新增 lazysizes 组件库，实现图片的惰性加载
- cdn 统一更换为 bootcss 源
- 升级 fancybox、mathjax 版本，并配置 fancybox 相关参数

### 4 日

- 博客各组件添加阴影效果

### 3 日

- 添加 markdownlint 规范化 markdown 格式，并添加钩子函数

### 2 日

- 移动端的目录按钮调整位置并添加阴影效果

### 1 日

- 修改 post 模板
- 移动端最大宽度由 800px 变为 1040px

## 3 月

### 31 日

- 添加 coding 部署方式

### 30 日

- 实现文章小图大图的不同加载，以及添加水印的效果

### 28 日

- 将图片迁移到七牛云，并采用 hexo-qiniu-sync 实现自动上传
- 删除多余的 mdui，next 主题

### 25 日

- 添加 hexo-tag-aplayer 音乐播放器

### 24 日

- 限制文章图片的最大高度为 250px

### 22 日

- 字号由 20px 变为 18px
- 修复移动端头像不在中间的 bug

### 21 日

- 上一页，下一页由英文变为中文

### 18 日

- 更换网站头像，添加头像旋转变色特效

### 17 日

- 代码自动检测由 true 改为 false

## 2 月

### 24 日

- github 上传方式由 https 变为 ssh

# 2017 年

## 12 月

### 24 日

- 发现文章头部的几天前是静态数据，去掉此功能

### 15 日

- git-cz 选项提交，commitlint 提交格式规范工具，conventional-changelog 生成 changelog 日志，并在 husky 中添加响应执行脚本
- 更换网站头像
- 添加文章头部几天前提示（后来被验证错误，因为是静态网站的原因）

### 12 日

- 左边栏宽度由 500px 调整到 400px

### 10 日

- 添加谷歌分析 id

### 9 日

- 将每页长度由 5 个更改为 10 个

### 7 日

- 添加两个博客背景
- 将博客基础字号 18px 调整为 20px
- 调整无序列表项样式
- 调整左边栏宽度
- 将目录最大级数由 3 级放宽到 6 级

### 6 日

- 将博客基础字号 20px 调整为 18px

## 11 月

### 29 日

- 用`PS`图片压缩优化网站头像

### 28 日

- 添加子标题
- 更改网站描述`技术博客`为`博客`，考虑到要写非技术的文章
- 每页长度由 10 页更改为 5 页，为了网页加载更快
- 增加 seo 组件`hexo-generator-seo-friendly-sitemap`
- 添加百度站长验证
- 添加百度统计
- 添加 addthis 统计 id，改变 addthis 样式
- 更改头像样式
- 增加 hexo-fs 组件
- 增加 husky 组件，添加钩子脚本
- 包管理工具 npm 变更为 yarn

### 23 日

- 修复 gitalk 评论问题
- 域名由 http://towavephone.github.io/ 变为 https://towavephone.github.io
- 采用 sweetalert2 添加复制成功弹窗
- 更换百度分享链接为 https，因百度不支持 https，更换分享组件为 addthis
- github 上更换域名为 www.towavephone.com
- 关闭 github_widget 组件

### 22 日

- 添加文章加密功能，采用 hexo-blog-encrypt 开源库
- 添加 mdui 主题
- 因对友言评论样式不满意，改变评论为 gitment
- 改变评论为样式更漂亮的 gitalk

### 19 日

- 博客初始化提交，采用 yelee 样式
- 增加文章置顶功能
- 开启 github_widget 功能
