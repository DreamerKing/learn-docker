

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