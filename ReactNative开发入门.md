# ReactNative 开发入门

最近有个移动端POC项目基本谈妥，比较简单的原型演示型APP，不需要后台数据支撑。这个是不错的项目，让前端的成员拓展技能树。

用 React Native 开发移动项目成本相对低，支持跨平台，适合预算少、调取外部原生少的项目。

React Native 的生态已经比较成熟了，我们的前端技术栈也比较熟悉 React.js 的生态，而数据的绑定团队成员熟悉 dva 那套机制。

Dva 框架里最核心的数据绑定、通知机制，是在 dva-core 这个组件里；React-Native 里的路由功能用 react-navigation 库。

典型的 package.json 中的依赖示例：

```json
"dependencies": {
    "dva-core": "^1.3.0",
    "react": "16.6.3",
    "react-native": "0.57.8",
    "react-navigation": "^2.5.1",
    "react-navigation-redux-helpers": "^2.0.2",
    "react-redux": "^5.0.7"
}
```

开发环境搭建好之后，跑一下示例教程（windows系统上跑安卓模拟器或手机真机联调）

接着，这个脚手架项目： https://github.com/nihgwu/react-native-dva-starter 可以多参考。



#### 主要参考资料：

https://reactjs.org/   官方网站（英文）

https://reactnative.dev/  官方入门（英文）

https://reactnative.cn/  中文镜像站

https://reactnative.cn/docs/getting-started.html  搭建开发环境

https://reactnative.cn/docs/tutorial.html  示例教程：Hello World

https://github.com/nihgwu/react-native-dva-starter  ReactNative + dva 脚手架项目

https://github.com/dvajs/dva/issues?q=native  dva项目下大家关于ReactNative的问题

#### 其他示例：

https://www.jianshu.com/p/312a8f345735

https://www.jianshu.com/p/7faa78d0d172