# Docker-monitoring


使用`cadvisor + influxdb + grafana` 配置 Docker 监控


## Usage 


克隆后，在 `docker-compose.yml` 文件当前目录下执行

```
 docker-compose -f docker-compose.yml up -d
```

执行完毕后，使用 `docker ps -a` 可以查看启动的相关容器

Note:确保您已经安装 `docker-compose`，相关信息可查看官方安装教程 [Install Docker Compose](https://docs.docker.com/compose/install/)



## 关于 Web 访问


InfluxDB 访问：`http://localhost:8083`，Connection Settings 可设置 `influxDB` 连接信息

cAdvisor 访问：`http://localhost:8080`

Grafana 访问： `http://localhost:3000`，用户名默认为 `admin` ，密码为 `admin`


## 自定义 yml 文件

#### docker-compose.yml

可按实际自行修改 `docker-compose.yml` 中的 ports 等信息

