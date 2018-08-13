> Dart有两种运行模式：

> * 检查模式（checked）：进行类型检查，如果发现实际类型与声明或期望的类型不匹配就报错
> * 生产模式（production）：不进行类型检查，忽略声明的类型信息，忽略 assert 语句

> **检查模式运行较慢，生产模式运行快**

> 但检查模式可以及早地发现程序在的问题，所以建议在开发过程中使用检查模式，而在正式环境中使用生产模式运行

> idea 默认运行命令：`/Users/fuxiaosong/develop/dart/dart-sdk/bin/dart --checked --enable-vm-service:59821 /Users/fuxiaosong/develop/dart/project/studydart/bin/main.dart`

>可知 idea 默认是在检查模式下运行，而 Dart VM 模式是在生产模式下运行

> **Dart 2 已经只有生产模式了，废弃了检查模式**

---

> Dart 语言已经开始稳定，Dart 团队正在改进性能。Dart VM 已经在两个重要的基准测试中比 Chrome 使用的 JavaScript V8 引擎快很多了。

---

> Dartium：嵌入了 Dart VM 的 Chromium

---

> Every Dart app is a library, even if it doesn’t use a library directive.