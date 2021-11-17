# demo-project-
build the docker image by using exting node:alpine image 
using config folder expose port no  for mongodb and my sql and web servers 
establishing connections between the mongodb and web 
then after run docker container for web 
i have been putting the these 3 services in docker-compose by using docker-compose.yml file 
docker-compose is easily to devlop aand deploy the multiple containers in easy way 
docker-compose up -d --build i ran thise command when i succesfully putting the containers in docker-compose.yml
i had recheck my containers are activate or not by using docker ps command  
docker logs conatainer id or conatainer name  thse comand helps me to show the last 50 log files of related conatiners  if there any issue in conayiners running we can easily troubleshooting useing these logs 
i entering to my running containers using docker exec -it container name bash 
after my checking all containers its all have been activated mode and its are open to conecting the server 
by using my public ip :51005 
