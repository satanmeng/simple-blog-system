#使用文件作为数据载体的PHP博客系统

v0.2.0

##程序说明

页面说明：
* /boot.php 定义常量、函数
* /index.php 首页列表 
* /article.php 文章内容 
* /admin.php 后台文章列表管理 
* /admin_del.php 删除文章 
* /admin_edit.php 编辑文章 
* /template 视图目录
* /src 资源目录
* /data 存放数据文件的目录


##特性：
* 视图和逻辑分离
* 使用文件作为内存存储
* 没有使用面向对象和数据库
* 没有权限系统

##todo
* 实现注册、登录
* 增加权限控制
* 增加数据库支持
* 实现路由和控制器
* 实现orm
