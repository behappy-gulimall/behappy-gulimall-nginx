# behappy-gulimall-nginx
Nginx（用于本地开发，静态资源代理以及后端反代）

## 配置

- docker-compose.yml

> 修改文件中的$LC一值，将其改为宿主机/本机的host
> 这里会在upstream中进行配置，进而路由到你的网关服务


## 启动

- 在根目录执行`docker-compose up -d`
