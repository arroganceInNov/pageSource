---
title: Hexo
date: 2020-12-24 13:46:01
tags: [建站, 框架]
---

### 安装
1. 先安装好 [node.js](https://nodejs.org/) 和 [git](https://git-scm.com/)
2. 执行命令
```
npm install -g hexo-cli
```
3. 执行命令
```
hexo init <folder>
cd <folder>
npm install
```
完整的 hexo 项目就安装好啦
---

### 网站图标
1. 可以去 [favicon.io](https://favicon.io/) 生成自己喜欢的 icon 文件并下载到本地
2. 将 .ico 文件放到路径 themes/主题名/source/image/favicon.ico
3. 修改主题配置文件中的 favicon 路径
```
# _config.yml

favicon: /image/favicon.ico
```
大功告成
