# redis
windows下启动redis
1.启动redis服务器,并指定配置文件 
redis-server.exe redis-windows.conf 
2.启动redis客户端,指定ip,端口,密码 
redis-cli.exe -h localhost -p 6379 -a 123 
3.如果提示NOAUTH Authentication required. 
执行 auth "密码"即可
