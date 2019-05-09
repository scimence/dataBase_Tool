# dataBase_Tool

#### 介绍
MySql数据库合并工具（合并同一服务器下，两个数据库文件。要求数据库中拥有相同的表，表中结构相同，表中数据不同）


#### 使用说明

REM 使用数据库合并工具dataBase_Tool合并数据库abc2到->abc
REM 10.80.9.31:3309 数据库地址
REM game game@2015.run 用户名密码
REM 偏移表player、guild中的主键id信息
REM player.name、guild.name 对player表name列去重名、guild表name列去重名

java -jar dataBase_Tool_20170712_16.05.jar 10.80.9.31:3309 game game@2015.run abc abc2 player guild player.name guild.name
pause