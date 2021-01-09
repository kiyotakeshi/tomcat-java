# Tomcat Docker

## How to use

```shell
$ docker-compose up -d

$ docker-compose ps

$ curl http://localhost:8888/sample/
hello

$ docker-compose exec tomcat-sample

$ docker-compose down
```

- you can deploy war file under webapps directory
