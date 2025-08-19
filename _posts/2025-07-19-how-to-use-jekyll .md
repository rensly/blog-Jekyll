---
layout: post
title:  "使用Jekyll创建一个博客"
date:   2025-08-19 10:08:57 +0800
categories: jekyll update
---

[官方教程](https://docs.github.com/zh/pages/quickstart)

目标：
使用Jekyll创建一个博客。

## 什么是Jekyll？
- **静态网站生成器**：将Markdown文件转换为HTML网站
- **GitHub Pages原生支持**：无需额外配置即可使用
- **主题丰富**：提供多种现成的主题和布局
- **插件系统**：扩展功能的插件生态系统

## 使用Jekyll主题
- **选择主题**：从Jekyll主题库或GitHub Pages支持的主题中选择
- **配置_config.yml**：自定义网站标题、描述和其他设置
- **创建内容**：使用Markdown编写博客文章和页面
- **本地预览**：使用Jekyll本地服务器预览网站

主要步骤：
1. 建立git仓库
2. 配置pages环境
3. 本地建立jekyll项目
4. 编辑博客预览
5. 上传

## 如何建立本地预览
1、安装Jekyll和Bundler
参考 [官方教程](https://jekyllrb.com/docs/installation/)
```
# 安装Jekyll和Bundler
gem install jekyll bundler

# 检查 Jekyll 是否已正确安装：
jekyll -v
```
2、本地预览
# 启动本地服务器
bundle exec jekyll serve
```

## 如何写博客
1、在_posts目录下，新建文件

格式"年-月-日-文件名.md",`2025-07-19-how-to-use-jekyll.md`

2、本地预览查看效果。

3、git上传。


