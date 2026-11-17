# Web Fiction: 10 分钟速通 Web 前端

一个纯 HTML/CSS/JavaScript 的交互叙事网页。故事以“10 分钟速通 Web 前端”为设定，通过按钮、隐藏文本、章节跳转和状态切换推进剧情。

## 功能

- 多章节分支剧情
- 按钮选择与隐藏元素
- 鼠标选中文字触发彩蛋
- 独立章节样式
- 无构建依赖，可直接静态部署

## 运行

直接双击 `index.html`，或者启动静态服务器：

```powershell
python -m http.server 8080
```

打开 <http://localhost:8080>。

## 部署到 GitHub Pages

在仓库设置中选择：

```text
Settings -> Pages -> Build and deployment -> Deploy from a branch
Branch: main
Folder: / (root)
```

入口文件是 `index.html`，会自动跳转到 `chapter1.html`。

## 项目结构

```text
web-fiction/
├─ index.html
├─ chapter1.html
├─ chapter2.html
├─ chapter3.html
├─ scripts.js
├─ styles.css
├─ chapter2/
└─ chapter3/
```

## 说明

这是早期 Web 前端练习项目，主要展示 DOM 操作、CSS 样式和章节式交互。页面没有后端依赖。
