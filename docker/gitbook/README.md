# gitbook 镜像

[import, title:"Dockerfile", lang:"text"](Dockerfile)

```bash
# 创建镜像
sudo docker build -t gitbook-custom linux/docker/gitbook
# 运行容器
sudo docker run -v "$PWD:/www" --name=chengwanlu-com-build gitbook-custom
```