# 欢迎使用Era.js引擎！

## 引擎简介(Introduction)

[Era.js]() 是一个由 [Typescript]()+[Python]() 构建的、 以 [Python]()+[KJML]() 为游戏脚本的 ，基于 [Electron]() 程序平台和 [Semantic UI]() 样式库等技术开发的次世代跨平台“类Era”富文本游戏引擎。

## 快速入口(Quick Entry)

- [项目主页]()
- [文件下载]()



- [快速开始](Quick Starts/README.md)
- [教程](Tutorials/README.md)
- [文档](Documents/README.md)
- [API 引用](API References/README.md)

## 哲学

### 内涵而非外观

文字冒险游戏的游戏性并不是画面所产生的，而是由在牺牲画面之后，解放出来的生产力投入在游戏逻辑、数据系统的上面所产生的。

### 联合而非妥协

将最适合于前端的语言与最适合于处理文本的语言进行结合，从而赋予文字冒险游戏最为自由的创作表现力。这也是为什么引擎采取前后端异构的原因。

## 特性一览(Features)

### 集成前/后端最新技术

- 引擎语言：前端Typescript程序(静态/适配工程化开发)+后端Python库(动态/灵活)
- 游戏脚本：Python脚本+KJML逻辑文本标记语言

### 面向使用者优化

- 面向游戏开发者
- 面向游戏玩家
- 面向游戏二次开发者

### 强大的样式框架

- 内置了成熟、美观的 Semantic UI 样式库
- 内置了标准且高可自定义的 Span Charm 样式库(自研)

### 跨平台

- Electron的跨平台特性可以支持桌面端
  - [x] Windows
  - [ ] OS X
  - [x] Linux
- 从Electron中抽离出来的Era.js-web技术可以移植到Webview
  - [ ] Android
  - [ ] iOS
- 也可通过Era.js-Server部署到服务器，实现全终端多人连线（需相关游戏支持）
  - 