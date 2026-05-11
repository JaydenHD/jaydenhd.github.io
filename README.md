# JaydenHD Blog

这是 JaydenHD 的 GitHub Pages 个人博客，基于 Hugo 和 Ananke 主题构建。

## 本地预览

```powershell
hugo server -D
```

## 生成静态文件

```powershell
hugo --gc --minify
```

推送到 `main` 分支后，GitHub Actions 会自动构建并发布到 GitHub Pages。
