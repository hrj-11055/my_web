# MarkHuang个人项目博客
这是一个基于Jekyll的个人项目展示和博客网站，用于展示个人简历、项目介绍和技术博客。

## 项目概述
本项目是一个静态网站，使用Jekyll框架构建，并部署在GitHub Pages上。网站包含以下主要内容：

- 个人简历 ：展示个人教育背景、工作经历和技能
- 项目展示 ：展示个人完成的项目作品
- 技术博客 ：分享技术心得、项目经验和学习笔记
## 技术栈
- Jekyll ：静态网站生成器
- Markdown ：内容编写
- GitHub Pages ：网站托管
- Chirpy主题 ：网站主题
## 目录结构
```
.
├── _config.yml          # 网站配置文件
├── _posts/              # 博客文章目录
│   ├── 2023-01-01-hello-world.md
│   └── 2025-06-12-welcome-to-jekyll.
markdown
├── about.md             # 关于我页面
├── projects.md          # 项目展示页面
├── index.md             # 首页
└── Gemfile              # Ruby依赖管理文件
```
## 本地开发
### 环境要求
- Ruby 2.5.0 或更高版本
- RubyGems
- GCC 和 Make
### 安装步骤
1. 克隆仓库
```
git clone https://github.com/hrj-11055/
my_web.git
cd my_web
```
2. 安装依赖
```
bundle install
```
3. 本地运行
```
bundle exec jekyll serve
```
4. 在浏览器中访问 http://localhost:4000 查看网站
## 内容更新
### 添加新博客
在 _posts 目录下创建新的 Markdown 文件，文件名格式为 YYYY-MM-DD-title.md 。文件开头需要包含以下 YAML 头信息：

```
---
layout: post
title: "文章标题"
date: YYYY-MM-DD HH:MM:SS +0800
categories: [分类1, 分类2]
tags: [标签1, 标签2]
---
```
### 更新项目
编辑 projects.md 文件，按照现有格式添加新项目。

### 更新个人信息
编辑 about.md 文件，更新个人简介、教育背景、工作经历和技能等信息。

## 部署
本网站部署在GitHub Pages上，访问地址： https://hrj-11055.github.io/my_web

### 部署步骤
1. 将更改推送到GitHub仓库
```
git add .
git commit -m "更新内容"
git push
```
2. GitHub Actions会自动构建和部署网站
## 自定义
### 修改配置
编辑 _config.yml 文件，可以修改网站标题、描述、URL、社交媒体链接等信息。

### 更换主题
当前使用的是Chirpy主题，如需更换，请修改 _config.yml 文件中的 theme 或 remote_theme 设置。

## 联系方式
- GitHub: hrj-11055
- 邮箱: 1415994589@qq.com
## 许可证
MIT License

renjie huang

复制

删除

好的，接下来生成该readme文件

Trae

renjie huang

复制

删除

接下来生成该readme文件

Trae

renjie huang

复制

删除

接下来生成该readme文件

Trae

renjie huang

复制

删除

接下来生成该readme文件