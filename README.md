# Zhengyu Zhuang — Personal Website

一个无需构建工具的响应式个人学术网站，可直接部署到 GitHub Pages。

## 本地预览

在项目目录运行：

```powershell
python -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 部署到 GitHub Pages

1. 将本目录提交并推送到名为 `<你的 GitHub 用户名>.github.io` 的仓库。
2. 在仓库的 **Settings → Pages** 中选择从 `main` 分支根目录部署。
3. 等待 GitHub Pages 完成发布。

个人内容位于 `index.html`，视觉样式位于 `styles.css`，交互逻辑位于 `script.js`。替换 CV 时请保留文件名 `assets/Zhengyu_Zhuang_CV.pdf`，或同步修改页面中的链接。
