# 使用 Docker 构建 php 开发运行环境

LAMP=Linux+Apache+Mysql+PHP

LNMP=Linux+Nginx+Mysql+PHP

## 启动开发环境
```sh
docker-compose -f "docker-compose-dev.yml" up -d --build 
```
访问
```
http://localhost:8080
```
## 关闭开发环境
```sh
docker-compose -f "docker-compose-dev.yml" down
```

## 启动生产环境
```sh
docker-compose -f "docker-compose.yml" up -d --build 
```
## 关闭生产环境
```sh
docker-compose -f "docker-compose.yml" down 
```