```markdown
# Parakeet

一个快速、开源、轻量级的前端框架。

[![Build Status](https://img.shields.io/github/workflow/status/Gadfly810/parakeet/CI/master)](https://github.com/Gadfly810/parakeet/actions?query=workflow%3ACI)
[![License](https://img.shields.io/github/license/Gadfly810/parakeet)](LICENSE)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/Gadfly810/parakeet)](https://github.com/Gadfly810/parakeet/releases)

Parakeet 是一个快速、开源、轻量级的前端框架，用于构建用户界面。
它被设计为简单、易用且高性能。

## 特性

*   响应式数据绑定
*   组件化架构
*   虚拟 DOM
*   轻量级（Gzip 压缩后小于 10KB）
*   现代 JavaScript (ES6+)
*   支持 TypeScript
*   工具链支持 (Webpack, Vite)

## 安装

你可以通过 npm 或 yarn 安装 Parakeet：

```bash
npm install parakeet
```

```bash
yarn add parakeet
```

## 使用

要使用 Parakeet，只需将其引入 HTML 并初始化：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parakeet App</title>
</head>
<body>
    <div id="app"></div>

    <script src="path/to/node_modules/parakeet/dist/parakeet.min.js"></script>
    <script>
        const app = new Parakeet({
            el: '#app',
            data: {
                message: 'Hello, Parakeet!'
            },
            template: `
                <div>
                    <h1>{{ message }}</h1>
                    <button @click="changeMessage">Change Message</button>
                </div>
            `,
            methods: {
                changeMessage() {
                    this.message = 'Welcome to Parakeet!';
                }
            }
        });
    </script>
</body>
</html>
```

更多示例请查阅文档。

## 文档

有关如何使用 Parakeet 的详细信息，请查阅我们的[文档](https://github.com/Gadfly810/parakeet/wiki)。

## 贡献

我们欢迎贡献！请查阅我们的 [CONTRIBUTING.md](CONTRIBUTING.md) 文件了解更多详情。

## 许可证

Parakeet 根据 [MIT 许可证](LICENSE) 发布。

## 联系方式

如果你有任何问题或建议，请随时联系：

*   邮箱: [gadfly810@gmail.com](mailto:gadfly810@gmail.com)
*   GitHub: [Gadfly810/parakeet](https://github.com/Gadfly810/parakeet)
```
