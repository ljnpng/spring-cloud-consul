## 测试 consul 服务发现

### consul docker 安装

```bash
docker run -d --name=consul -p 8500:8500 consul:1.15.4
```
> consul 没有 latest tag,所以使用 1.15.4


### 分别启动客户端和服务端

### 查看 concul 可以看到服务有注册的情况

> http://127.0.0.1:8500

### 访问服务

> http://127.0.0.1:8082/consume
