#	<img src="https://p1.meituan.net/dpgroup/0bc47eab6e17ac64a88539968e3ae8fc91606.png" height="80"/>

###### _美团点评内测中，即将发布_

duxjs是一款基于redux+react的高扩展可跟踪易上手的web前端业务框架。感谢 [ducks-modular-redux](https://github.com/erikras/ducks-modular-redux)和[choo](https://github.com/yoshuawuyts/choo))

[Enligsh](./README.md)

* **开发友好**

  * 声明式API
  * 不用再写redux式的样板代码，不需要在多个文件里来回切换
  * 通过generator function来承载异步任务
  * 好用的选择器，告别冗长的链式引用
  * hmr热替换

* **业务组件化**

  * 业务组件 = 业务逻辑+UI = action + effect + reducer + view(jsx)
  * 组件间隔离
  * 子组件申明与动态加载
  * 组件间通信
  * 组件可嵌套
  * 组件生命周期

* **同步与异步action**

  * 同步action
    * plain (可序列化) 意味着你能存储上报所有的action
    * 可追溯与可分析 每个action都会做来源标记(在哪个组件中被触发，被哪个action触发)
  * 异步action
    * 副作用(effect)实现基于generator function
    * 每个异步action都包含多个子的同步action，已预制的子action有START/SUCCESS/ERROR

* **插件系统**

  * 插件是一种增强后的业务组件
    * 插件中可订阅全局的effect/action/state变化/异常信息
    * 你可以在插件中使用已有的业务组件（每个plugin有自己的view）

* **服务端渲染（同构）**

  ​



![duxjs-logo](https://p0.meituan.net/dpgroup/14ae1d9491966089bdaedf4350aceab7126690.png)

