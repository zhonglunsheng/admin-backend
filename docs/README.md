# Getting Started
小型项目快速开发后台管理系统，常用技术集成、支持可配置。
- 权限管理 （用户登录+角色管理+接口权限）
- 系统管理 （服务器监控+在线日志查看+在线动态配置）

## 优势
> 对于目前很多后台管理系统开源项目，发现很多都是不断集成功能大而全，看上去确实牛逼、眼花缭乱
不管是基本的还是扩展的都放在一起，我要用这个框架不得不接受这些功能，要接受这些功能后期如果要维护不得不看这些代码
如果我仅仅只需要基本的增删查改，没有一个是精简的。我相信其实大部分后台管理系统有些是没那么复杂的，代码量这么多后面人维护确实很麻烦，能不能出现一个由用户自动选择功能的后台管理系统，
这个有点类似于微擎安装第三方模块的思路，基于语言的不同微擎后台开发是使用php语言，php是支持热部署的直接上源代码修改然后可以即刻生效，但java是多了一个打包的过程。
- 代码精简
> 目前采用单体结构只包含基本功能，项目不分层，有第三方功能会单独集成包来进行开发，如果不需要第三方功能可以直接相关删掉不影响主功能，支持单体改多体，易于`微服务架构`改造升级
- 支持可配置
> 可修改源代码配置和线上`动态配置` 功能可插拔 如果不需要某些功能可以直接在配置文件关闭和开启
- 前后端分离
> 采用前后端分离架构，不限制前端框架技术开发，后台只提供接口返回数据
- 功能可插拔
> 

# 更新日志
- 项目初始化 集成Springboot + Mybatis-plus + Druid
- 添加Swagger-ui logback日志框架
- 添加多数据源和SpringSecurity权限框架
- 添加代码自动生成
- 引用mybatis-plus自动代码生成插件
