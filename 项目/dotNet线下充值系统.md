# dotNet线下充值系统

##  1、开发环境搭建

  安装下列软件：


| 开发所需工具IDE / 数据库 | 版本 |
| ------------------------ | ---- |
| Visual Studio            | 2013 |
| Microsoft SQL Server     | 2014 |
|                          |      |

## 2、源码

1. 后端: D:\works\网站代码3\Admin
2. 前端：D:\works\网站代码3\Front
3. 数据库备份：D:\works\网站代码3\Admin\Backup

## 3、SQL Server身份验证

- (MicrosoftSQLServer，错误:18470)  原因:该帐户被禁用
- u: sa , p: root

> 解决方法：先用windows身份验证的方式登录进去，然后在‘安全性’-‘登录名’-右键单击‘sa’-‘属性’，选择“状态”选项卡，登录选择“启用”，是否允许连接到数据库引擎，选择“授予”，点击确定就可以了。

