# 李倩倩的21岁生日网站

## 运行方法
1. 解压文件夹（如果是压缩包）。
2. 双击 `index.html`，用浏览器打开即可预览。
3. 也可以用 VS Code / Codex 打开整个 `birthday-website` 文件夹继续修改。

## 自定义
- 修改标题：搜索 `Happy` 或 `A Letter for You`。
- 修改祝福语：编辑 `id="letterText"` 中的文字。
- 添加照片：将 `.photo-art` 里的 emoji 替换为 `<img src="images/photo1.jpg" alt="回忆照片">`，并把照片放入 `images` 文件夹；可设置 `img { width:100%; height:100%; object-fit:cover; }`。
- 愿望会尝试保存在当前浏览器的 localStorage 中。
- 页面字体使用 Google Fonts；若无网络，会自动回退到系统字体。
