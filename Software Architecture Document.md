by 15331118 hsk
### 架构问题 
- 前端微信小程序与后端服务器对接问题
- 当出现前端与后端数据不同步，导致数据冲突问题
- 多个请求同时出现时，后端数据库处理问题
### 解决方案说明 
- 利用MVC模型，解决可能出现的架构问题
- ![image](https://raw.githubusercontent.com/MengfanHe/photoes/master/%E6%95%B0%E6%8D%AE%E6%B5%81%E5%9B%BE.png)
- 后端利用python语言进行编写数据库与数据处理，使用Tornado Web Server构造web服务器框架
- 前端利用微信小程序进行渲染，利用微信提供的接口实现所需功能
### 逻辑视图 
![image](http://wx1.sinaimg.cn/mw690/c3b8fd03gy1fs45884cxsj20iw0hijrv.jpg)
### 物理视图 
![image](http://wx1.sinaimg.cn/mw690/c3b8fd03gy1fs45s4vtjoj20f00c874c.jpg)
