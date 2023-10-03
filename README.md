# MEME WIKI

## 개발 환경
- **SpringBoot** 3.1.4
- **Java** 17
- **Gradle** 8.2.1
- **Mysql** 8.0.31
- **Redis** 7.0.2
- **Swagger** springdoc

## 실행 환경
1) MySQL 실행 (Docker Container 사용)
```shell
docker run --name memewiki-mysql -e MYSQL_ROOT_PASSWORD=root1234! -d -p 3306:3306 mysql:8.0
```
2) Redis 실행 (Docker Container 사용)
```shell
docker run --name memewiki-redis -d -p 6379:6379 redis
```
