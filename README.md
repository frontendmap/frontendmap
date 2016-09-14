# FrontEndMap

### web 前端基础知识体系，系统、优质、开源

![](https://camo.githubusercontent.com/296599ca34161a124b0253c24d41d621cb0bb3ef/687474703a2f2f696d61676573323031352e636e626c6f67732e636f6d2f626c6f672f3133383031322f3230313630392f3133383031322d32303136303931343132333834353734322d3630373231333137302e706e67)

并不同于目前网络上的若干前端知识体系（例如[这个](https://segmentfault.com/a/1190000004070468)和[这个](https://my.oschina.net/hxwny/blog/499513)），FrontEndMap 考虑了 web 前端开发涉及到的所有过程，包括**源码环境 -> 构建过程 -> 服务器环境/node -> http -> 浏览器/webview**，其中会涉及到一些国际标准和规范，包括`ECMS262`、`W3C`、`http`、`nodejs API`等，其中还会在过程中介绍常用的工具，例如`React`、`angular`、`vue`、`webpack`、`jquery`等等。

FrontEndMap 希望能通过开源的力量，维护一个国内最权威的 web 前端知识体系指南，**欢迎大家 star、fork 并 PR** ，也欢迎大家[提交 issue](https://github.com/frontendmap/frontendmap/issues)。

# 开发环境

## 源码

### 物理结构

代码作为一个个物理文件该如何管理

- [版本管理 git](./source-env/source/physics/git.md)
- [第三方依赖管理 npm](./source-env/source/physics/npm.md)
- [javascript 模块化：AMD CMD commonJS ES6规范](./source-env/source/physics/js-module.md)
- [css module](./source-env/source/physics/css-module.md)

### 逻辑设计

前端开发需要掌握的设计知识，逻辑、抽象的能力

- [基本功，算法、数据结构等](./source-env/source/logic/basic.md)
- [设计模式](./source-env/source/logic/design-pattern.md)
- MVVM [Vue.js](./source-env/source/logic/vue.md) [Angular](./source-env/source/logic/angular.md)
- 组件化 [React](./source-env/source/logic/reactjs.md)


## 构建

用构建工具搭建前端代码框架，构建过程中常用的工具

- [模板引擎，如jade](./source-env/build/tpl.md)
- [语法糖，如less、sass](./source-env/build/sugar.md)
- [自动化测试、单元测试](./source-env/build/test.md)
- [lint 语法检查](./source-env/build/lint.md)
- [打包，webpack gulp等](./source-env/build/pack.md)

## 服务器/测试机

代码发布到服务器上之后，需要掌握的知识

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

浏览器下载到代码之后会渲染页面，还会遵守 W3C ECMA 的标准

- [渲染与性能优化](./browser/render.md)

- [开发者工具 & 调试](./browser/dev-tool.md)

- [ECMA262 标准](./browser/ecma.md)

### W3C 标准

W3C 标准中规定了日常开发中使用最多的 html、css、DOM API 等语法和规范。

- [html](./browser/w3c/html.md)
- [css](./browser/w3c/css.md)
- [WEB-API](./browser/w3c/web-api.md)
- [2D/3D](./browser/w3c/2d-3d.md)

# 其他

其他内容






