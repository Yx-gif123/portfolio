# 个人主页 · Personal Homepage

单文件静态个人主页（简历 / 作品集）。

## 特点
- 单文件 `index.html`，CSS / JS / 图片全部内联，**双击即可在浏览器打开**。
- 无构建、无 npm、无框架；仅外链 Google Fonts（在线时加载，离线自动回退系统字体）。
- 视觉风格：对称排版 / 章节叙事 / 复古印刷调色（韦斯·安德森《月升王国》气质）。

## 本地预览
直接用浏览器打开 `index.html`。

## 部署到 GitHub Pages
1. 新建 Public 仓库，把本目录（仅 `index.html` + 本 README）push 到 `main` 分支。
2. 仓库 → Settings → Pages → Source = Deploy from a branch → `main` / `(root)`。
3. 访问 `https://<用户名>.github.io/<仓库名>/`。

## 目录
| 文件 | 说明 |
|---|---|
| `index.html` | 主页本体（自包含） |
