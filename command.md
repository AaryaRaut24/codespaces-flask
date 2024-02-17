docker image ls
docker pull nginx
docker run --name nginx -p 80:80 nginx
docker ps -a
docker stop nginx
docker rm nginx
docker run --name nginx -p 8000:80 nginx
