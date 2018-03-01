# Docker-monitoring


使用`cadvisor + influxdb + grafana` 配置 Docker 监控


# Usage 


在 `docker-compose.yml` 文件当前目录下执行

```
 docker-compose -f docker-compose.yml up -d
```


Note:确保您已经安装 `docker-compose`，相关信息可查看官方安装教程 [Install Docker Compose](https://docs.docker.com/compose/install/)

打开浏览器访问 `http://localhost:3000`，默认用户名为 `admin` ，密码为 `admin`
