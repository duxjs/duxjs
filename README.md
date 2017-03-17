#	<img src="https://p1.meituan.net/dpgroup/0bc47eab6e17ac64a88539968e3ae8fc91606.png" height="80"/>

###### _I'm coming soon_

duxjs is a componentized  redux framework based on react , redux , react-redux. (Inspired by [ducks-modular-redux](https://github.com/erikras/ducks-modular-redux))

* **Developer friendly**

  * simpler api
  * generator function
  * mighty selector
  * hmr

* **Biz componentization**

  * biz component = biz logic + view = action + effect + reducer + view
  * isolation
  * declare child component and mount them dynamically
  * communication between parent and child
  * nestable
  * life cycle

* **Sync&async action**

  * sync-action
    * plain (serializable)
    * traceable and analysable
  * async-action
    * effect based on generator function
    * sub sync-action: START/SUCCESS/ERROR or other custom actions

* **Plugin system**

  * plugin is an enhanced biz component
    * plugin subscribe all global effects/actions/stateChanges/exceptions
    * you can use biz component in plugins

* **Server-side rendering**

  ​



![duxjs-logo](https://p0.meituan.net/dpgroup/14ae1d9491966089bdaedf4350aceab7126690.png)

