# DockerWeb
DockerLinux


docker  build -t  dockerweb .

docker run   --name  myappdocker -d -p 8083:80 --restart=always  dockerweb