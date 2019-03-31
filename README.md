# MySQL_First_Learning
MySQL学习打卡第一天

###MySQL安装启动

###使用图形界面软件Navicat for SQL

###数据库基础知识

###MySQL数据库管理系统

MySQL安装启动

教程群主都已经给了链接 所以这不再贴了 主要写一下我安装过程的一些错误经历。根据群主大大给出的链接 选择了zip压缩版本 然后进行解压 再用管理员身份进入cmd找到bin目录 开始注册mysqld --install mysql8再进行初始化mysqld --initialize --console 之后进行MySQL启动 在命令行输入 net start mysqld 然后是net start mysql显示启动成功 中间会出现一个初始密码用这个作为登入密码 之后可自行修改。但我搞丢了初始密码 没有及时记下 然后通过大神指导 在删除了data之后 再创建一个data文件 然后进入cmd重新初始化mysqld 就能拿到初始密码了。

Navicat for SQL

下载好了后 准备跟mysql连接 并复制了刚刚上面的初始密码 连接号可随意取 但发生了一个系统报错 具体如下图


        ![image]
        (https://github.com/MySQL_First_Learning/README.md/blob/master/
