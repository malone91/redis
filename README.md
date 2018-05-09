# redis
windows下启动redis
1.启动服务端:,并指定配置文件，cmd命令进到安装目录，键入以下命令： 
redis-server.exe redis-windows.conf 
2.客户端访问：
启动redis客户端,指定ip,端口,密码 
redis-cli.exe -h localhost -p 6379 -a 123 
3.如果提示NOAUTH Authentication required. 
执行 auth "密码"即可

