
# Google DevFest Workshop · Chrome DevTools MCP

一个多页面的静态站点，用来记录在 Google DevFest Workshop 中围绕 Chrome DevTools MCP Server 的体验。项目采用现代 UI 设计语言，包含首页以及三个主题子页面。

## 页面结构

- `index.html`：总览 Workshop 行程、亮点与数据。
- `gdg-devfest.html`：介绍 GDG 社区与 DevFest Workshop 的沉浸式体验。
- `devtools-mcp.html`：总结 Chrome DevTools MCP Server 的实践方法与落地场景。
- `about.html`：关于我的个人介绍与联系方式。

所有页面共用 `styles.css`，没有额外的构建或依赖。

## 本地预览

1. 在浏览器中打开 `index.html`（或任意页面）即可查看，推荐使用最新版 Chrome。
2. 如果需要通过静态服务器预览，可运行 `python3 -m http.server` 后访问 `http://localhost:8000/`。
3. 调整样式或内容后刷新浏览器，使用 DevTools 进行即时验证。
