# bookinfo-microservices

```
$ docker run -d --rm --name reviews-db -e MYSQL_ROOT_PASSWORD=password -v $(pwd)/hack/mysql:/docker-entrypoint-initdb.d:ro -p 3306:3306 mysql:8.0
```

```
$ curl http://localhost:8080/reviews?productId=0
```

```
$ docker build -t reviews:dev .
```
