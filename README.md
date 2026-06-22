# 摸鱼贪吃蛇 GitHub Pages 包

这是一个已经打包好的静态网站版本，适合直接发布到 GitHub Pages，或者打成压缩包发给朋友直接打开。

## 目录内容
- `index.html`：游戏主页面
- `manifest.webmanifest`：PWA 配置
- `sw.js`：离线缓存
- `icon.svg`、`icon-192.png`、`icon-512.png`：站点图标
- `.nojekyll`：避免 GitHub Pages 处理静态资源时出现额外限制

## 本地打开
- 直接双击 `index.html`
- 或把整个目录放到静态服务器上访问

## 发布到 GitHub Pages
最简单的方式有两种：
1. 把这个目录里的所有文件放到仓库根目录，或者放到 `docs/` 目录
2. 在 GitHub 仓库设置里开启 GitHub Pages，选择对应分支和目录

如果你已经有仓库，建议使用以下结构：
- `main` 分支
- `docs/` 目录存放这里的全部文件
- GitHub Pages Source 选择 `main /docs`

## 分享给朋友
如果你只是想先发给朋友玩：
1. 把整个 `github-pages/` 目录上传到任意静态托管
2. 把生成的网站链接发给朋友
3. 手机和电脑浏览器都可以直接打开

## 说明
- 支持触屏操作
- 支持 PWA 安装
- 最高分会保存在本地浏览器里
