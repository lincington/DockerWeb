# DockerWeb
DockerLinux


docker  build -t  dockerweb .

docker run   --name  myappdocker -d -p 9001:9001 --restart=always  dockerweb