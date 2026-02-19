---
title: "GitHub Pages 搭建教程"
date: 2026-02-18
---

手把手教你用 GitHub Pages 零成本搭建个人网站，全程不需要服务器。

## 什么是 GitHub Pages

GitHub Pages 是 GitHub 提供的免费静态网站托管服务，直接从仓库读取 HTML/Markdown 文件并渲染成网页。支持 Jekyll 主题，自带 HTTPS。

## 搭建步骤

### 第一步：创建仓库

1. 登录 GitHub，点击 **New repository**
2. 仓库名随意（如 `my-blog`），设为 **Public**
3. 勾选 **Add a README file**，点击 Create

### 第二步：开启 GitHub Pages

1. 进入仓库 → **Settings → Pages**
2. Source 选 **Deploy from a branch**
3. Branch 选 `main`，目录选 `/ (root)`，点击 **Save**

### 第三步：添加配置文件

创建 `_config.yml`：

```yaml
theme: minima
title: 我的博客
author: 你的名字
description: 一个简单的技术博客
