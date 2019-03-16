创建一个nodejs 环境

```
docker build -t hello-node .
docker run -p 8080:8088 hello-node
```

访问 8088 端口就可以访问了。。