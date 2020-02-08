### 安装mongo

```
$ sudo apt install mongodb
$ sudo service mongodb status
```

### 开启远程连接

```
$ sudo vim /etc/mongodb.conf
```

bind_ip 127.0.0.1 改为 bind_ip=0.0.0.0

重启mongo

```
sudo service mongodb status
```

