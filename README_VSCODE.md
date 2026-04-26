# 字迹练习生成器 - VS Code 工作包

这是你当前网页的 VS Code 工作包。主文件是：

- `index.html`

直接用 VS Code 打开本文件夹即可继续开发。

## 推荐运行方式

### 方式一：直接预览
双击 `index.html`，用浏览器打开。

### 方式二：VS Code 本地预览
1. 在 VS Code 中打开本文件夹。
2. 安装扩展：`Live Server`。
3. 右键 `index.html`。
4. 点击 `Open with Live Server`。

## 重要提醒

当前网页是单文件 HTML，里面包含：

- HTML 页面结构
- CSS 样式
- JavaScript Canvas 渲染逻辑
- 内嵌字体数据

文件较大是正常的，因为字体已经以 base64 形式写入文件中。

## 开发原则

后续让 AI 修改时，请明确要求：

- 不要重写整站
- 不要删除内嵌字体
- 不要改坏 V6 渲染逻辑
- 每次只改一个功能
- 修改前先定位相关函数
- 修改后检查 `index.html` 是否还能直接打开
