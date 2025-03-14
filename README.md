# 网页时装购物系统 / Web Fashion Shopping System

![SpringBoot](https://img.shields.io/badge/SpringBoot-2.x-brightgreen)
![MyBatisPlus](https://img.shields.io/badge/MyBatisPlus-2.3-blue)
![Shiro](https://img.shields.io/badge/Shiro-1.3.2-red)
![Vue](https://img.shields.io/badge/Vue-2.x-4fc08d)

# 项目简介  
基于 SpringBoot + MyBatis Plus + Shiro 的时装类电商平台，包含商品管理、购物车系统、用户权限控制、即时通讯模块，前端采用 Vue.js + Layui 实现多端界面交互。

# 特征介绍  
- ​**权限控制**：集成 Apache Shiro 实现后台管理系统的动态权限过滤。
- ​**高效开发**：MyBatis-Plus 简化单表 CRUD 操作，支持分页插件自动拦截。
- ​**文件管理**：封装 FileUtil 工具类实现图片上传与静态资源映射。
- ​**AI集成**：百度 AI SDK 支持智能图像处理功能（如商品图片识别）。
- ​**多端适配**：分离 admin（管理系统）与 front（用户端）双界面架构。
- ​**接口规范**：通过 VO/Model/View 分层实现数据格式标准化。

# 代码结构 
```
src/
├── main/
│   ├── java/
│   │   ├── com/
│   │   │   ├── annotation/          # 自定义注解
│   │   │   ├── config/              # 全局配置
│   │   │   ├── controller/          # 接口层
│   │   │   │   ├── AddressController.java
│   │   │   │   ├── CartController.java
│   │   │   ├── dao/                 # 数据访问层
│   │   │   ├── entity/              # 数据模型
│   │   │   │   ├── model/           # 业务模型
│   │   │   │   ├── view/            # 视图对象
│   │   │   ├── interceptor/         # 请求拦截器
│   │   │   ├── service/             # 服务层
│   │   │   │   ├── impl/            # 服务实现
│   │   │   ├── utils/               # 工具类
│   ├── resources/
│   │   ├── mapper/                  # MyBatis映射文件
│   │   ├── application.yml          # 主配置
│   │   ├── static/                  # 静态资源
│   │   │   ├── upload/              # 文件存储
```

# 使用说明
- 数据库配置：修改 application.yml 中数据库连接信息
- 后台地址：http://localhost:8080/springbootw3o95/admin/dist/index.html
- 管理员账号：abo/abo
- 前台入口：http://localhost:8080/springbootw3o95/front/index.html
- 推荐浏览器：Google Chrome

# 技术文档
* 核心框架：[Spring Boot](https://spring.io/projects/spring-boot)
* 持久层框架：[MyBatis-Plus](https://mybatis.plus) + [MyBatis Spring Boot Starter](https://mvnrepository.com/artifact/org.mybatis.spring.boot/mybatis-spring-boot-starter/2.1.1)
* 安全框架：[Apache Shiro](https://shiro.apache.org/)
* 工具库：[Hutool](https://www.hutool.cn) + [Fastjson](https://github.com/alibaba/fastjson)
* 前端框架: [Vue.js](https://vuejs.org/) + [Layui](https://layui.dev)
* AI服务：[百度AI开放平台](https://ai.baidu.com/)

# 捐赠
> 博主将持续更新Java全栈开发项目，包含ssm，springboot，前后端分离系统等项目。
> 此外如果您够宽裕，请博主喝杯咖啡吧！捐赠将用于服务器维护与开源社区建设，感谢您的认可！
> 如需更多Java相关项目毕设3000+，sql文件可联系博主v:xq-lucky311
![输入图片说明](%E7%91%9E%E5%B9%B8%EF%BC%81%E7%91%9E%E5%B9%B8%EF%BC%81.png)