# CentOS 7 学习笔记

Todo: SSH 和 SFTP 都不用记了(bushi


用户的添加和删除

添加使用的命令是: useradd 该命令会自动创建和用户同盟的 home目录
> 而使用 useradd -d 命令则可以使指定的目录作为用户的 Home目录

删除使用的命令是: userdel 该命令将删除用户，但保留home目录
> userdel -r 该命令将删除用户和用户的home目录

查询用户信息

>id 加上 username

可以查询用户信息

当用户不存在时，返回无此用户