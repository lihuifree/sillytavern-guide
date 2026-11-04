# 酒馆手记

两篇互补的 SillyTavern 使用笔记：第一篇介绍玩法、记忆、基础功能与预设；第二篇介绍类脑社区的作品、书单、主题赛事、找卡与参与交流的方式，并衔接 Club 的酒馆入门博文。

发布地址：[酒馆手记](https://lihuifree.github.io/sillytavern-guide/)。

社区篇：[认识类脑：酒馆角色卡背后的创作社区](https://lihuifree.github.io/sillytavern-guide/leinao/)。

## 文件

- `index.html`：文章正文、页面结构和分享摘要。
- `article.md`：同一篇文章的 Markdown 原文，方便阅读与修改。
- `leinao/index.html`：类脑社区介绍的独立页面。
- `leinao/article.md`：社区篇 Markdown 成稿，可从页面下载。
- `styles.css`：桌面、手机和打印样式。
- `favicon.svg`：本站图标。
- `.nojekyll`：让 GitHub Pages 直接发布静态文件。

纯 HTML/CSS，无构建步骤、JavaScript、远程字体或第三方依赖。目录链接和资源路径适用于 GitHub Pages 项目站点。

## 预览与维护

在此目录运行 `python3 -m http.server 8765`，然后打开 `http://localhost:8765/`，社区篇路径是 `/leinao/`。修改正文时同步更新该篇的 `article.md` 与 `index.html`；网站直接发布静态 HTML，不会自动把 Markdown 转成网页。改动推送到 `main` 后，GitHub Pages 会自动部署。
