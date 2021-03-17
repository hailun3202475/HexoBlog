title: "koa"
---

**什么是koa**   

koa是一个新的WEB框架   

利用async函数丢弃回调函数，增强错误处理。（使用同步的写法去执行异步的函数）   

没有任何预置的中间件



**koa核心概念**  

koa Application(应用程序)  

Context (上下文)  

request（请求）、response (相应)   



**koa核心概念**

洋葱模型执行的顺序：顺序执行

回调的顺序：反向执行

先进后出



**koa中间件**

路由：koa-router

协议解析： koa-body

跨域处理： @koa/cors

路由压缩： koa-combine-routers

静态资源： koa-static