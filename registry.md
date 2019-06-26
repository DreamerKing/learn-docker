```
docker run -d -p 5000:5000 --restart always -v $PWD/registry:/var/lib/registry  --name registry registry:2

docker tag todo:1.0.0  127.0.0.1:5000/todo:1.0.0
docker push 127.0.0.1:5000/todo:1.0.0
```

注册中心相关项目
[distribution](https://github.com/docker/distribution) 
[registry](https://hub.docker.com/_/registry)
https://github.com/docker/distribution/blob/v2.2.1/docs/storagedrivers.md