# behappy-gulimall-nginx
Nginx（静态资源代理以及后端反代）- docker版本

## 配置

- 修改conf.d/upstream.conf，将地址改为宿主机/本机的地址
- 修改host，host指向你的宿主机/虚拟机地址
```agsl
127.0.0.1 gulimall.com
127.0.0.1 search.gulimall.com
127.0.0.1 item.gulimall.com
127.0.0.1 auth.gulimall.com
127.0.0.1 cart.gulimall.com
127.0.0.1 order.gulimall.com
127.0.0.1 member.gulimall.com
127.0.0.1 seckill.gulimall.com
```

## 启动

- 在根目录执行`docker-compose up -d`
