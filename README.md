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
