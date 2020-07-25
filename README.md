# docker-commands

docker build -t <image-name> .  
docker run -p 4000:4000 <image-name>  
docker ps  

docker stop <container_id>  
docker start <container_id>  

docker container ls -a  
docker image ls  
docker container rm <container_id>  
docker image rm <image_id>  
docker rmi <image-id>  

==================================================================  
docker-compose build  
docker-compose up -d <container_name>  
docker logs <container_name>  
docker-compose down  

docker pull <container_id>  

==================================================================  
docker run -ti ubuntu:lalest bash  
cat /etc/lsb-release  
exit  

docker ps --format #FORMAT  

docker run (image to container)  
docker commit (container to image)  

docker ps -l --format=$FORMAT  
docker commit {container_id) 

docker tag {image_id} my-image  

docker commit {container_name} my-image-2  

=================================================================  
docker build -t springio/gs-spring-boot-docker .  
command builda an image and tag it as springio/gs-spring-boot-docker  
mkdir -p target/dependency && (cd target/dependency; jar -xf ../*.jar)  

=================================================================  
build image using maven command  
./mvnw spring-boot:build-image -Dspring-boot.build-image.imageName=springio/gs-spring-boot-docker  
