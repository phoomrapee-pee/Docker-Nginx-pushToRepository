# Docker-Nginx-pushToRepository
------Version 1 ------- 
เป็นการทำ docker-compose : 04-Code\0-Docker\Docker-Nginx-pushToRepository\nginx-compose\
 การสร้าง docker image ด้วย docker commit พร้อมกับ push ไปยัง docker repository

use port 9001\

------Version 2 -------\
เป็นการทำ dockerFile : 0-Docker\Docker-Nginx-pushToRepository\nginx-dockerImage
docker build -t nginx-test . \


docker run --name my-custom-nginx -d nginx-test \ 


#sudo docker commit [CONTAINER_ID] [new_image_name] \
docker commit 67037246f5ce phoomrapee/nginx-helloworld:2.0\

docker push phoomrapee/nginx-helloworld:2.0\

