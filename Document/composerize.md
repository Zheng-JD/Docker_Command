## Composerize：将常见 docker 命令转换为 docker-compose 文件格式

composerize 是一个可以将常见的 Docker 命令行转换为 docker-compose 文件格式的小工具，而它本身除了可以通过命令行转换，还可以直接在网页上进行转换。

**1.网页版转换：** https://www.composerize.com/

**2.命令转换：**

需要先安装 nodejs ：
```
npm install composerize -g
```

使用命令转换成docker-compose.yml 格式的内容：
```
composerize docker安装命令
```

举例：
```
composerize docker run -p 80:80 -v /var/run/docker.sock:/tmp/docker.sock:ro --restart always --log-opt max-size=1g nginx
```
