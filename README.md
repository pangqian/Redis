# Redis
只需要双击redis-server.exe程序就可以启动Redis服务,一般服务我们都是用Windows Service来启动的
sc create Redis start= auto DisplayName= Redis binpath= "F:\Study\No-Sql\Redis\redis-windows\RedisService.exe"
其中RedisService是Redis注册Windows服务的启动程序通过上面的脚本就可以成功安装Redis为Windows Service了，然后每次系统启动的时候，就会自动开启Redis服务，而不需要我们每次去手动运行redis-server.exe命令了
