---
title: Hexo
date: 2020-12-24 13:46:01
categories: IT
tags: 建站
---

### 安装
1. 先安装好 [node.js](https://nodejs.org/) 和 [git](https://git-scm.com/)
2. 执行命令
```sh
npm install -g hexo-cli
```
3. 执行命令
```sh
hexo init <folder>
cd <folder>
npm install
```
完整的 hexo 项目就安装好啦
---

### 网站图标
1. 可以去 [favicon.io](https://favicon.io/) 生成自己喜欢的 icon 文件并下载到本地
2. 将相应文件放到路径 $主题所在位置/source/images/
3. 修改主题配置文件中的 favicon 路径，以 next 主题为例
```yml
# _config.yml

favicon:
  small: /images/favicon-16x16-next.png
  medium: /images/favicon-32x32-next.png
  apple_touch_icon: /images/apple-touch-icon-next.png
```
大功告成
