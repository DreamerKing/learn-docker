

Docker是开发者和系统管理员用来开发、部署和运行应用的容器平台。使用Liunx容器来部署应用的过程叫做容器化，它具有以下特点：
+ Flexible: Even the most complex applications can be containerized.
+ Lightweight: Containers leverage and share the host kernel.
+ Interchangeable: You can deploy updates and upgrades on-the-fly.
+ Portable: You can build locally, deploy to the cloud, and run anywhere.
+ Scalable: You can increase and automatically distribute container replicas.
+ Stackable: You can stack services vertically and on-the-fly.

查看版本
```
docker --version
```

查看镜像间依赖
```
docker image inspect --format='{{.RepoTags}} {{.Id}} {{.Parent}}' $(docker image ls -q --filter since=b707620d204c)
```

+ 镜像
+ 层
+ 容器
+ 仓库

创建镜像的方式
1. 从运行容器的某个时刻通过`docker commit`创建
2. 通过Dockerfile
3. 通过Dockerfile及配置管理工具
4. 导入所需文件从头创建

