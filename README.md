**郑重声明：项目经过本地测试，确保可以运行。项目仅供学习和毕业设计参考~**

![输入图片说明](qrcode_for_gh_1266b4b5294a_258.jpg) 发送BS028，体验一下~

#### 1.项目介绍

技术栈+环境：SpringBoot + jsp + mysql5.7及以上 + maven3 + idea2022

系统角色：管理员、普通用户（学生）

系统功能：管理员（座位预订管理、座位使用统计、自习室管理、违规与投诉、学校大楼管理、预约时间管理、公告管理等）、学生（座位预订信息、座位预订、咨询与投诉等）

#### 2.项目部署

- 创建数据库，导入项目提供的sql文件

- 根据本地数据库环境修改数据库连接，src/main/resources/application.properties  13-16行

- 启动项目，http://localhost:8080/seatmis/

- 管理员账号/密码： admin/admin  学生账号/密码：15162385972/123456 或者查看huiyuan表