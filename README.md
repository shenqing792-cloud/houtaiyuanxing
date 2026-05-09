# 发行运营后台原型

这是一个用于需求评审演示的静态后台原型项目。

## 页面入口

- `index.html`：平台封禁页面原型。
- `components.html`：组件沉淀入口，可切换查看筛选项、列表内容、添加/编辑窗口组件。

## 使用方式

直接用浏览器打开 HTML 文件即可预览。后续也可以发布到 GitHub Pages、静态资源服务器或内网 Web 服务，方便在其他电脑访问演示。

## 发布建议

推荐发布到 GitHub Pages：

1. 新建 GitHub 仓库并推送本项目。
2. 在仓库 `Settings / Pages` 中选择 `Deploy from a branch`。
3. 分支选择 `main`，目录选择 `/root`。
4. 发布后访问 `https://<github用户名>.github.io/<仓库名>/components.html` 或 `index.html`。

临时局域网演示也可以在项目目录启动静态服务：

```powershell
python -m http.server 8080
```

同一局域网内其他电脑访问 `http://<本机IP>:8080/components.html`。
