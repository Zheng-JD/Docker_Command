# Docker 教程

#### [composerize – 将 Docker 命令行转换为 docker-compose 文件格式](/Document/composerize.md)  

# Docker 常用命令

### 清除容器缓存

```
docker system prune --volumes
```

可清除以下容器的缓存：
- 所有停止的容器
- 所有不被任何一个容器使用的网络
- 所有不被任何一个容器使用的volume
- 所有无实例的镜像

### 
