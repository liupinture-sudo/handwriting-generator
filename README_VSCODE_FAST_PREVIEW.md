# 手写生成器 VS Code 快速预览版

这个版本只做了一件事：把原来 index.html 中内嵌的 4 个超大 base64 字体拆到 `fonts/` 文件夹中。

这样 Live Server 打开时不会长时间白屏加载。功能逻辑、V6 渲染效果、字体库、滑块参数都没有改。

## 使用方式

1. 用 VS Code 打开本文件夹。
2. 安装 Live Server 插件。
3. 右键 `index.html`。
4. 选择 `Open with Live Server`。
5. 浏览器打开后，等待字体加载完成即可使用。

## 注意

部署到 Vercel/GitHub 时，要同时上传：
- `index.html`
- `fonts/` 文件夹

不要只上传 index.html，否则字体会丢失。
