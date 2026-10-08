# 谱见｜工业过程智能感知与分析

这是一个纯静态个人网站，适合部署到 GitHub Pages、Netlify 或 Vercel。

## 文件说明

- `index.html`：页面内容、文章卡片、导航与 SEO 信息
- `style.css`：颜色、字体、布局、响应式样式
- `script.js`：光谱图、峰位开关、代码复制、订阅反馈和移动菜单
- `.nojekyll`：让 GitHub Pages 直接发布静态文件

## 本地预览

在此文件夹中运行任意静态服务器，例如：

```text
python -m http.server 4173
```

然后打开 `http://localhost:4173`。

## 发布到 GitHub Pages

1. 在 GitHub 新建公开仓库。
2. 上传 `index.html`、`style.css`、`script.js`、`.nojekyll` 和 `README.md`。
3. 打开仓库的 `Settings → Pages`。
4. 选择 `Deploy from a branch`、`main` 分支和 `/ (root)` 目录。
5. 保存后等待 GitHub 生成网站地址。

如果使用 GitHub Copilot，可以在仓库中打开这些文件，让 Copilot 按文件注释协助修改；修改后提交到 `main` 分支，GitHub Pages 会自动更新。
