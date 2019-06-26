1. 构建镜像 
```
docker build -t tage-name image-name .
```
2. 查看镜像
```
docker image ls
docker images
docker image ls -a
```

3. 删除镜像
```
docker image rm <imags-hash>
docker rmi <imags-hash>
docker rmi $(docker image ls -a -q)
```

4. 打标签
```
docker tag <image> uername/repository:tag
```

5. 登录docker Hub
```
docker login
```

6. 推送镜像
```
docker push uername/repository:tag
```