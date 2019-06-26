运行Wordpress
```
docker run --name wp-mysql -e MYSQL_ROOT_PASSWORD=123 -d mysql
docker run -d -p 10002:80 --name blog --link wp-mysql:mysql tutum/wordpress
```