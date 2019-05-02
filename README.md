# Gin BBS App

## 项目目录结构
<details>
<summary>展开查看</summary>
<pre><code>
├── app              项目核心逻辑代码
│    ├── auth        用户相关
│    ├── controllers 控制器
│    ├── helpers     工具方法
│    ├── models      模型
│    ├── policies    权限校验
│    ├── requests    参数校验
│    ├── services    复杂查询
│    └── view_models 数据转换
│
├── config           配置中心
│
├── database         数据库
│    └── factory     数据 mock
│
├── middleware       中间件
│    └── wrapper     controller 包裹函数
│
├── pkg              项目依赖
│
├── public           项目静态文件
│
├── resources        前端源码
│    └── view        go 模板文件
│
├── routes           路由
│    └── routes.go   路由注册
│    └── api.go      api 路由注册
│    └── web.go      页面路由注册
│    └── named       命名路由模块
│
├── storage          存放日志等文件
│
├── main.go          项目入口
│
├── config.yaml      项目配置
│
├── deploy.sh        部署脚本
│
└── Makefile         Makefile 文件
</code></pre>
</details>

## 实现功能
- [x] CSRF 验证
- [x] flash 消息闪现
- [x] 记忆上次表单提交的数据
- [x] 参数校验模块
- [x] 命名路由
- [x] 分页
- [x] 发送邮件
- [x] 用户权限模块
- [x] 日志
- [x] 前端构建 (typescript、sass ...)

***