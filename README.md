# 酒馆手记

一篇 SillyTavern 入门文章，以自己的 GPTClub 中转接入为例，介绍请求编排、agent 与记忆的区别、上下文管理、基础功能、小猫之神与夏瑾预设，以及类脑社区的资源入口。

发布地址：[酒馆手记](https://lihuifree.github.io/sillytavern-guide/)。

## 文件

- `index.html`：文章正文、页面结构和分享摘要。
- `article.md`：同一篇文章的 Markdown 原文，方便阅读与修改。
- `styles.css`：桌面、手机和打印样式。
- `favicon.svg`：本站图标。
- `.nojekyll`：让 GitHub Pages 直接发布静态文件。

纯 HTML/CSS，无构建步骤、JavaScript、远程字体或第三方依赖。目录链接和资源路径适用于 GitHub Pages 项目站点。

## 预览与维护

在此目录运行 `python3 -m http.server 8765`，然后打开 `http://localhost:8765/`。修改正文时同步更新 `article.md` 与 `index.html`；网站直接发布静态 HTML，不会自动把 Markdown 转成网页。改动推送到 `main` 后，GitHub Pages 会自动部署。
