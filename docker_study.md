## docker安装

1. 登陆你的ubuntu
```
	which wget
```

如果wget没有安装

``` linux
	sudo apt-get update 
	sudo apt-get install wget
```

2. 获取最新版本

```
	wget -qO- https://get.docker.com/ | sh
```

3. 验证是否安装成功

```
	docker run hello-world
```
