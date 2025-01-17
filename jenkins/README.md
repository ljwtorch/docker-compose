#### Jenkins docker-compose

注：此部署文件由[Jenkins官方文档](https://www.jenkins.io/zh/doc/book/installing/#docker)中的`docker run`命令修改而来，增加了挂载宿主机`docker-compose`的命令

#### 快速开始

1. 环境准备
   - Docker
   - Docker Compose
2. 启动服务：执行`docker-compose up -d`来自动拉取镜像和部署；
3. 访问服务： [http://localhost:8080](http://localhost:8080/)；
4. 执行`docker logs -f jenkins`或者在持久化目录执行`cat secrets/initialAdminPassword`查看密钥，格式为`f12838a0e58b4a9782d3a3632776226f`；
