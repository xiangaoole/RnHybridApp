# RnHybridApp

这是一个 React Native 项目，目前只有 android 子模块 [incubator](https://github.com/xiangaoole/incubator)。

你可以通过拉取本项目包括其子模块的代码：

```bash
git clone git@github.com:xiangaoole/RnHybridApp.git
git submodule init # 初始化子模块的本地配置文件
git submodule update # 取所有数据并检出父项目中列出的合适的提交
```

一段时间后，你可以需要更新 android 子模块到最新：

```bash
git status # 查看 android 子模块是否需要更新
git submodule update --remote
```

更多子模块的操作，请参考 [Git 工具 - 子模块](https://git-scm.com/book/zh/v2/Git-%E5%B7%A5%E5%85%B7-%E5%AD%90%E6%A8%A1%E5%9D%97)
