# 快速开始（Quick Starts）

## 用Era.js开发自己的文字游戏最少需要几步？

### 第一步：下载 Era.js 游戏引擎及开发依赖

#### 下载 Python3.7

[Python3 下载地址](https://www.python.org/downloads/windows/)

<img src="1570965013343.png" alt="1570965013343" style="zoom: 50%;" />

[Era.js 引擎下载地址](https://github.com/miswanting/Era.js/releases)

### 第二步：工程初始化



### 第三步：编写你自己的代码

```python
import erajs.api as a  # 导入引擎 API

a.init()               # 游戏引擎初始化
a.t('Hello World!')    # 显示文本
```

更加复杂的代码，参见[教程]()

### 第四步：调试游戏

## 用Era.js发布自己的文字游戏最少需要几步？

### 第一步：打包游戏

### 第二步：没了

## 下一步

- 教程：由浅入深，从基础开始学习引擎使用方法；
- 文档：分专题了解
- API 参考：

[Era.js]() 是一个由 [Typescript]()+[Python]() 构建的、 以 [Python]()+[KJML]() 为游戏脚本的 ，基于 [Electron]() 程序平台和 [Semantic UI]() 样式库等技术开发的次世代跨平台“类Era”富文本游戏引擎。

## 快速入口(Quick Entry)

- [项目主页]()
- [文件下载]()



- [快速开始]()
- [教程]()
- [文档]()
- [API 引用]()

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