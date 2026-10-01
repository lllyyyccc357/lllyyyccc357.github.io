# 梁奕宸的个人网站

纯 HTML/CSS 网站，无需安装依赖。首页、简历、学习笔记和项目展示。

## 本地预览

在本目录运行 `python3 -m http.server 8000`，浏览器访问 http://localhost:8000。

## 文件

- `index.html`：首页、简历和项目内容
- `assets/style.css`：页面样式和手机适配
- `notes/first-note.html`：第一篇建站笔记，可复制为新文章并在首页添加链接
- `.nojekyll`：直接发布静态文件

简历尚未提供，页面相应部分明确标记为待补充。上传公开版 PDF 后，再添加真实下载链接。

## 首次发布

1. 在 GitHub 创建公开仓库 `lllyyyccc357.github.io`，不要初始化 README、许可证或 .gitignore。
2. 本地完成 GitHub 身份认证后运行 `git push -u origin main`。
3. 仓库 Settings → Pages → Source 选择 Deploy from a branch，分支 main，目录 /(root)，保存。
4. 在 Actions 中确认部署成功，再访问 https://lllyyyccc357.github.io/。

## 后续更新

```bash
git status
git add .
git commit -m "更新网站内容"
git push
```

只把准备公开的文件放在这个仓库中。上一级 materials 文件夹保存原始资料，不在此 Git 仓库内。
