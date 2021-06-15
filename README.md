# docker
纯属总结学习
docker search 关键字  检索镜像<br/>
docker pull 拉取 镜像<br/>
docker images 镜像列表<br/>
docker rmi image-id 删除镜像 ex：如果镜像被某个容器运用了，就要先删除容器 <br/>
docker rm container-id 删除容器<br/>
docker ps 查看运行中的容器 -a 查看所有的容器 <br/>
docker start、stop container-id 或 container-name 启动关闭容器<br/>
docker run -d -p port1:port2 --name 容器名称 容器  启动容器<br/>
docker exec -it container-id bash 进入容器环境<br/>
ctrl+p+q 退出容器 如果使用exit 退出后会关闭容器 <br/>
docker ps ｜ grep container-id 查看容器状态 <br/>
docker logs container-id 查看容器日志<br/>
docker commit -m "message" -a "author" container-id new_container_name 容器打包 <br/>
docker push  registerUrl/image_name
