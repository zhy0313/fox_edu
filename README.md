# 简介
一个基于django以及xadmin的在线教育平台。
# 开发环境
- 开发工具：Pycharm
- 开发环境：Python 2.7（Virtualenv）、django==1.9、xadmin==0.6.1
- 数据库：MySQL
- 第三方库：django-simple-captcha==0.4.6（验证码）、django-pure-pagination（分页）、 pillow（图像处理）
- 第三方服务：七牛云（视频存储）
# 功能介绍
## 用户注册
包括登录、注册、找回密码（邮箱），注册和找回密码会通过图片验证码验证以及通过邮箱验证方式完成。
## 后台管理系统
将model注册到xadmin中，并完成xadmin的全局配置
## 课程机构
通过templates模板继承机制实现模板的重用，主要包括分页、筛选、收藏等功能，并通过modelform对表单进行验证和保存。
## 课程功能
包括课程列表功能实现、课程详情页展示、 课程评论功能和相关课程推荐等功能。
## 课程讲师功能
授课讲师的列表页和详情页讲师信息的展示。
## 个人中心
包括个人信息的展示和修改、 头像修改、密码修改、邮箱修改（通过邮箱验证）。用户学习的课程展示、用户的收藏展示以及删除收藏功能，最后是用户的个人消息展示。
## 全局搜索功能
包括全局导航栏功能和全局搜索功能。 
## 404以及500页面配置
配置系统的全局404和500页面
# Model设计

