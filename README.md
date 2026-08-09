# 小红书购物人格 DNA 测试

这是可直接部署到 GitHub Pages 的单层静态页面包。

## 部署方法

1. 将本目录内的全部文件上传到 GitHub 仓库根目录，不要改变文件名或建立子文件夹。
2. 打开仓库的 `Settings` → `Pages`。
3. 在 `Build and deployment` 中选择 `Deploy from a branch`。
4. 选择存放这些文件的分支和根目录 `/ (root)`，然后保存。
5. 等待 GitHub Pages 发布完成后访问生成的网址。

## 文件说明

- `index.html`：页面入口。
- `app.js`：页面逻辑和交互。
- `styles.css`：页面样式和动画。
- `.nojekyll`：确保 GitHub Pages 按静态文件原样发布。
- `*.svg`：首页、题目、结果、小票和分享页视觉素材。

所有资源都使用相对路径，既可以部署在用户主页，也可以部署在项目子路径。项目没有独立的 PNG、JPG 或 JPEG 文件；位图内容已经内嵌在 SVG 中，以保证显示效果一致。
