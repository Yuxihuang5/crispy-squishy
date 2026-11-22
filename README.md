# Cyber Crunch｜赛博脆皮捏捏

一个无需后端的互动网页小游戏，支持电脑鼠标和手机触屏操作。包括多种捏捏物体的脆皮碎裂、局部揉捏回弹、音效及响应式布局。

## 在线部署到 GitHub Pages

1. 登录 GitHub，点击 **New repository**，新建一个公开仓库，例如 `cyber-crunch`。
2. 将本文件夹中的 `index.html`、`README.md`、`.gitignore` 和 `.nojekyll` 上传至仓库**根目录**（不是新建的子文件夹）。提交文件。
3. 打开仓库 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**；选择 `main` 分支和 `/ (root)`，点击 **Save**。
5. 部署完成后，地址通常为：`https://你的用户名.github.io/cyber-crunch/`（以 GitHub Pages 页面实际显示的链接为准）。

## 本地预览

直接双击 `index.html`，用 Chrome、Safari 等浏览器打开即可。第一次播放音效可能需要先点击网页，这是浏览器的自动播放限制。

## 文件说明

- `index.html` — 网站页面、样式、交互代码和已内嵌的图片／音频资源，**无需另外上传素材文件**。
- `README.md` — 使用和部署说明。
- `.gitignore` — 排除系统及编辑器临时文件。
- `.nojekyll` — 告诉 GitHub Pages 直接发布静态文件。

## 注意

这是纯静态网页，不需要安装 Node.js、购买服务器或设置 API Key。GitHub Pages 用于公开托管静态网站；上传前请确认对所用图片、音效有相应的发布权利。
