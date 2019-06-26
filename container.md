1. 启动容器
```
docker run -p -d 4000:80 <image>
```

2. 查看运行容器
```
docker container ls
```

2. 查看所有容器
```
docker container ls --all
docker container ls -aq
```

3. 停止容器
```
docker container stop <hash>
```

4. 强制关闭容器
```
docker container kill <hash>
```

5. 删除容器
```
docker container rm <hash>
docker container rm $(docker container ls -a -q)
```
