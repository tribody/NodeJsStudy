# NodeJsStudy
本代码来自[Node入门](https://www.nodebeginner.org/index-zh-cn.html)。

一个基本的web服务器可以由这四部分组成：
 - index.js
 - server.js
 - router.js
 - requestHandler.js

`index.js`是web服务器的入口点，`server.js`创建服务器，`router.js`提供路由服务，根据不同请求分发任务，`requestHandler.js`为实际的web处理程序。通过模块化js能够很好地完成功能模块之间的解耦和代码的复用。Javascript语言本身是单线程的，但是node是多线程的。
