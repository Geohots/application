# application

通讯系统 - 练习版

# Redis
执行下面命令获取redis包 需要到GOPATH路劲下执行  我的这里时cd到GoProgram执行go get github.com/garyburd/redigo/redis  
go get github.com/garyburd/redigo/redis   
import "github.com/garyburd/redigo/redis"

# Mysql
redis数据持久化与写入mysql   
引入数据库中间件kingshard实现Mysql数据库服务

# 编译client
PS D:\GoProgram> go build -o client.exe  application/client/main

# 编译服务器
PS D:\GoProgram> go build -o server.exe application/server/main
