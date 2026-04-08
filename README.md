# 李艳丽 - 个人主页

纯静态个人网站，使用 HTML + CSS + JavaScript 构建，通过 GitHub Actions 自动部署到 GitHub Pages。

## 功能

- 响应式设计，适配桌面和移动端
- 深色 / 浅色主题切换（跟随系统偏好）
- 滚动入场动画
- 数字递增动画
- 导航高亮跟随滚动位置

## 部署

推送到 `main` 分支后自动部署。需在 GitHub 仓库设置中：

1. 进入 **Settings > Pages**
2. Source 选择 **GitHub Actions**

## 本地预览

直接用浏览器打开 `index.html`，或使用任意静态服务器：

```bash
npx serve .
```
