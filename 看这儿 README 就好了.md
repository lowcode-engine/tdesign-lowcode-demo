如果构建过程中控制台发生错误，十有八九都是这个错误（https://github.com/alibaba/lowcode-engine/issues/301）

```
node v16.17.1
npm 8.15.0
win10
以上环境下可运行
```

虽然官网仓库推荐使用 yarn，但物料没打通前不建议使用 yarn，yarn 虽然也能安装本地宝，但是它有缓存，如果不更改本地包的版本号，那么就不无法安装新本地包，除非每次都更改本地宝的版本号，用 npm 就不会用这个问题。

只需关注 packages/tdeisgn-lowcode-demo 这个包

不清楚的可以查看 git 历史提交记录

本仓库没有提交 package-lock.json，因此重新 npm i 后很可能无法运行

本仓库基于 https://github.com/alibaba/lowcode-demo 0d1ea74 检出

配套文章：
[阿里低代码引擎 | LowCodeEngine - 如何将新组件库接入物料，以TDesign为例
](https://juejin.cn/post/7296412955477655567)