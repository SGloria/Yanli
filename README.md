# Yanli

个人主页，纯静态站点（HTML + CSS + JS），零依赖，零构建，推送即部署。

**在线访问** &rarr; [sgloria.github.io/Yanli](https://sgloria.github.io/Yanli/)

## 项目结构

```
.
├── src/                 # 站点源码（GitHub Pages 部署目标）
│   ├── index.html
│   ├── style.css
│   ├── main.js
│   └── favicon.svg
├── docs/                # 个人文档存档（不部署）
├── .github/workflows/
│   └── deploy.yml       # GitHub Actions 自动部署配置
├── .gitignore
└── README.md
```

## 技术选型

| 选型 | 说明 |
|------|------|
| 纯 HTML/CSS/JS | 无框架、无构建工具，打开即用 |
| CSS 变量 | 驱动浅色/深色主题切换 |
| IntersectionObserver | 滚动入场动画 & 导航高亮 |
| Google Fonts | Inter + Noto Serif SC + Noto Sans SC |
| GitHub Actions | push 到 `main` 自动部署到 GitHub Pages |

## 本地预览

直接打开 `src/index.html` 即可，或用任意静态服务器：

```bash
npx serve src
```

## 部署

推送到 `main` 分支后 GitHub Actions 自动触发部署。首次需要在仓库中配置：

1. **Settings &rarr; Pages &rarr; Build and deployment**
2. Source 选择 **GitHub Actions**

## License

MIT
