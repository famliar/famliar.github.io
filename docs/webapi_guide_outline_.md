# Web API 学习文档

## 1. **Web API概述**
   - **什么是API（Application Programming Interface）？**
     - API的定义及其重要性
     - API与Web API的区别
   - **Web API的作用**
     - 提供跨平台、跨系统的数据通信和集成
     - 支持前后端分离的架构模式
   - **常见的Web API类型**
     - REST（Representational State Transfer）
     - SOAP（Simple Object Access Protocol）
     - GraphQL

## 2. **RESTful API基础**
   - **什么是REST架构？**
     - REST的六大约束条件
       - 客户端-服务器
       - 无状态（Stateless）
       - 可缓存（Cacheable）
       - 分层系统（Layered System）
       - 统一接口（Uniform Interface）
       - 按需代码（Code on Demand，可选）
   - **HTTP协议基础**
     - HTTP方法（GET, POST, PUT, DELETE, PATCH等）
     - HTTP状态码（2xx, 3xx, 4xx, 5xx）
     - 请求和响应的结构
       - 请求头、响应头、请求体和响应体
     - MIME类型（如`application/json`, `application/xml`等）
   - **REST API的设计原则**
     - 资源和路径设计
     - 使用HTTP动词来定义操作
     - 状态码的合理使用

## 3. **SOAP与GraphQL API简介**
   - **SOAP（Simple Object Access Protocol）**
   - SOAP是一种协议，主要用于企业级应用程序的集成。它依赖XML进行消息传递，并且通常与WSDL（Web Services Description Language）一起使用，定义服务的接口。
   -  ****
