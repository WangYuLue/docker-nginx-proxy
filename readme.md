# 通过 nginx 代理模拟生产环境

## how to use?

```bash
# 启动
docker-compose up -d

# 停止
docker-compose down

# 更换静态文件
将静态文件 放到 html 目录下

# 修改 nginx 配置
编辑 conf.d/default.conf 文件

# 更改配置后，需要重启 nginx
docker-compose restart
```
