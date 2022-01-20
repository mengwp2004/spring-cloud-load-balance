
#参考：
https://spring.io/guides/gs/spring-cloud-loadbalancer/


# 启动
## 1 启动 say hello,在终端启动3个服务，只是端口不一样
mvn spring-boot:run

SERVER_PORT=9092 mvn spring-boot:run

SERVER_PORT=9999 mvn spring-boot:run

## 2 启动user

## 3 在浏览器里运行 localhost:8888/hi




