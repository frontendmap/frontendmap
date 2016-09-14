# FrontEndMap

### web 前端知识体系，系统、优质、开源

FrontEndMap 希望能通过开源的力量，维护一个国内最权威的 web 前端知识体系指南，**欢迎大家 star、fork 并 PR** ，也欢迎大家[提交 issue](https://github.com/frontendmap/frontendmap/issues)。

并不同于目前网络上的若干前端知识体系（例如[这个](https://segmentfault.com/a/1190000004070468)和[这个](https://my.oschina.net/hxwny/blog/499513)），FrontEndMap 考虑了 web 前端开发涉及到的所有过程，包括**`源码环境 -> 构建过程 -> 服务器环境/node -> http -> 浏览器/webview`**，其中会设计到一些国际标准和规范，包括`ECMS262`、`W3C`、`http`、`nodejs API`等，其中还会在过程中介绍常用的工具，例如`React`、`angular`、`vue`、`webpack`、`jquery`等等。如下图：

![](https://camo.githubusercontent.com/296599ca34161a124b0253c24d41d621cb0bb3ef/687474703a2f2f696d61676573323031352e636e626c6f67732e636f6d2f626c6f672f3133383031322f3230313630392f3133383031322d32303136303931343132333834353734322d3630373231333137302e706e67)

正文开始……

# 开发环境

## 源码

### 物理结构

一个系统的源代码是由若干个文件夹、若干个文件组成的一个物理结构，其中的代码作为一个一个的物理文件该如何归置？还有代码版本管理和第三方插件的依赖管理该如何处理？这都属于代码的物理结构。

- [版本管理 git](./source-env/source/physics/git.md)
- [第三方依赖管理 npm](./source-env/source/physics/npm.md)
- [javascript 模块化：AMD CMD commonJS ES6规范](./source-env/source/physics/js-module.md)
- [css module](./source-env/source/physics/css-module.md)

### 逻辑设计

系统的设计是一种逻辑的、抽象的结构，和任何一个物理文件都没有关系，因此这单独区分处理。例如，“模块化”和“组件化”两个看似难以区分，其实前者是物理的，后者是逻辑的。

- [基本功，算法、数据结构等](./source-env/source/logic/basic.md)
- [设计模式](./source-env/source/logic/design-pattern.md)
- MVVM [Vue.js](./source-env/source/logic/vue.md) [Angular](./source-env/source/logic/angular.md)
- 组件化 [React](./source-env/source/logic/reactjs.md)


## 构建

相比几年之前“蛮荒时代”的前端开发，构架工具的产生是的前端开发这几年飞速进化和发展。现在所有的前端项目代码，都会使用构建工具搭建前端代码框架。

- [模板引擎，如jade](./source-env/build/tpl.md)
- [语法糖，如less、sass](./source-env/build/sugar.md)
- [自动化测试、单元测试](./source-env/build/test.md)
- [lint 语法检查](./source-env/build/lint.md)
- [打包，webpack gulp等](./source-env/build/pack.md)

## 服务器/测试机

将代码上传到服务器（互联网项目普遍使用 linux 服务器，windows 系统此处忽略）上，要学会常用的 linux 命令，还要掌握 vim 编辑器来高效率的编辑文档。如果是 nodejs 项目，还要了解 nodejs 的相关知识。

- [linux 命令](./server/linux-command.md)
- [vim](./server/vim.md)
- [nodejs](./server/nodejs.md)

## 网络

服务器和客户端的交互基于 http 协议，会用到 socket ajax 等技术，以及一些常见的性能优化

- [http](./net/http.md)
- [socket](./net/socket.md)
- [ajax/fetch](./net/ajax-fetch.md)
- [性能优化](./net/performance.md)

## 浏览器 / webview

代码加载到浏览器之后，浏览器需要解释、执行代码并绘制成最终的页面，其中可能会涉及性能优化。在这个渲染过程中，浏览器是要遵守 ECMA262 和 W3C 标准来执行的，因此要了解这两个标准的主要内容。如果页面有问题，还需要使用开发者工具或其他工具来调试程序。

- [渲染与性能优化](./browser/render.md)

- [开发者工具 & 调试](./browser/dev-tool.md)

- [ECMA262 标准](./browser/ecma.md)

### W3C 标准

W3C 标准中规定了日常开发中使用最多的 html、css、DOM API 等语法和规范。W3C 内容非常多，还有一提案状态未发布的内容，因此只需要掌握其重点内容即可。

- [html](./browser/w3c/html.md)
- [css](./browser/w3c/css.md)
- [WEB-API](./browser/w3c/web-api.md)
- [2D/3D](./browser/w3c/2d-3d.md)

# 其他

其他内容






