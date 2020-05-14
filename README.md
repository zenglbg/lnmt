# lnmt

- linux + nginx + mysql + tomcat
- 一键 docker 环境

## docker 安装

- [docker 下载地址](https://docs.docker.com/engine/install/)
- [docker-compose 下载地址](https://docs.docker.com/compose/install/)

## docker 教程

- [教程地址](https://www.kancloud.cn/thinkphp/weekly/1293369)

## 配置

- 将.war 包放入 www 目录。tomcat 自动打包
- docker/config 配置 nginx 代理 tomcat

## 启动

- 敲以下命令启动服务

```
# /bin/bash

# 命令行敲入
docker-compose up
# 命令行敲入进入后台运行模式
docker-compose up -d

```

- nginx 配置域名的修改 hosts 访问
