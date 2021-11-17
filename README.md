# demo-project-
build the docker image by using exting node:alpine image 
using config folder expose port no  for mongodb and my sql and web servers 
establishing connections between the mongodb and web 
then after run docker container for web 
i have been putting the these 3 services in docker-compose by using docker-compose.yml file 
docker-compose is easily to devlop aand deploy the multiple containers in easy way 
docker-compose up -d --build i ran thise command when i succesfully putting the containers in docker-compose.yml
i had recheck my containers are activate or not by using docker ps command  
docker logs conatainer id or conatainer name  thse comand helps me to show the last 50 log files of related conatiners  if there any issue in containers running we can easily troubleshooting useing these logs 
i entering to my running containers using docker exec -it container name bash 
after my checking all containers its all have been activated mode and its are open to conecting the server 
by using my public ip :51005 
![Screenshot (39)](https://user-images.githubusercontent.com/78895362/142188333-0ce7f757-b0a9-425e-836e-a7847a789022.png)
![Screenshot (35)](https://user-images.githubusercontent.com/78895362/142188382-f3721511-e9d7-490b-9cda-c2570ad23757.png)
![Screenshot (34)](https://user-images.githubusercontent.com/78895362/142188419-4bacabd9-28d5-4025-899c-f23137ada6f3.png)
![Screenshot (38)](https://user-images.githubusercontent.com/78895362/142188491-bc75fad2-b628-4290-8043-494e133c4105.png)

