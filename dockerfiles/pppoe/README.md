**描述**: PPPoE Dockerfile 配置文件

部署

```
# docker build --tag pppoe .
```

运行

```
# docker run --detach --net host --privileged --env INTERFACE=eth0 pppoe
```

帐户信息

```
用户名: test
密码: test
```