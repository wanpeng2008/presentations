# Flutter 开发介绍

## 一、Flutter技术介绍

### 1. 什么是Flutter

Flutter是谷歌的移动UI框架，可以快速在iOS和Android上构建高质量的原生用户界面。 Flutter可以与现有的代码一起工作。在全世界，Flutter正在被越来越多的开发者和组织使用，并且Flutter是完全免费、开源的。

* 快速开发

    毫秒级的热重载，修改后，您的应用界面会立即更新。使用丰富的、完全可定制的widget在几分钟内构建原生界面。

* 富有表现力和灵活的UI

    快速发布聚焦于原生体验的功能。分层的架构允许您完全自定义，从而实现难以置信的快速渲染和富有表现力、灵活的设计。

* 原生性能

    Flutter包含了许多核心的widget，如滚动、导航、图标和字体等，这些都可以在iOS和Android上达到原生应用一样的性能。

### 2. flutter 与相关移动开发技术概念澄清

* android: java => kotlin

    Oracle版权之争，安全、简洁、实用，以及与 Java 可交互良好

* ios: objective-c => swift

* flutter, dart

    跨平台框架

* Google Fuchsia

### 3. Flutter发展历程

* 2015年, 第一个版本“Sky”在Dart开发者峰会上亮相

    以每秒120帧的速度持续渲染。

* 2018年2月，世界移动大会公布Beta1版本。

* 2018年12月， 发布1.0版本

* 2019年9月，GDD发布1.9版本

### 4. Flutter在国内大厂的应用情况

* 阿里

* 腾讯

* 滴滴、拼多多、百度等跟进

> 以hybrid的场景为主，在已有app内引入flutter的代码

![Flutter架构图](assets/flutter_architecture.jpeg)

## 100. 参考资料

1. 为什么Flutter会选择 Dart ？

    https://www.imooc.com/article/51068

    Dart是同时非常适合AOT编译和JIT编译的少数语言之一（也许是唯一的“主流”语言）。

    Flutter最受欢迎的功能之一是其极速热重载。在开发过程中，Flutter使用JIT编译器，通常可以在一秒之内重新加载并继续执行代码。

    预编译的AOT代码比JIT更具可预测性，因为在运行时不需要暂停执行JIT分析或编译。

    AOT编译代码还有一个更大的优势，那就是避免了“JavaScript桥梁”。当动态语言（如JavaScript）需要与平台上的本地代码互操作时，它们必须通过桥进行通信，这会导致上下文切换，从而必须保存特别多的状态（可能会存储到辅助存储）。这些上下文切换具有双重打击，因为它们不仅会减慢速度，还会导致严重的卡顿。Flutter通常比动态语言所需的桥快几个数量级。

2. 咸鱼在flutter hybrid应用经验分享

    Release Flutter的最后一公里

    https://yq.aliyun.com/articles/609644/

