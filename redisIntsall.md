### 安装redis-server

```
$ sudo apt update
$ sudo apt install redis-server
$ sudo service redis status
```

### 开启远程连接

```
sudo vim /etc/redis/redis.conf
```

将 bind 127.0.0.1 ::1 改为 bind 0.0.0.0

之后重新启动 redis

```
$ sudo service redis restart
```

