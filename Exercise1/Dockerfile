FROM ubuntu:22.04

RUN apt-get update -y
RUN apt-get install figlet -y   
# CMD exec fidget -f slant "Hello World"
ENTRYPOINT [ "figlet" ]


# In Terminal:

# *Build Image*
# docker build -t figlet .
# *Run Specific Image with name*
# docker run -it --name=figlet figlet

# docker run figlet hello

# *Upload Image to Docker Hub*
# docker build -t dansoler/figlet:1.0.0 .
# docker push dansoler/figlet:1.0.0

# *Get Container*
# docker ps
# docker ps -a
# *Get Images*
# docker images
# docker rm

# pip list
# pip list | findstr Flask >> requirements.txt

# Create app.py

# *Run Flask (server)*
# python3 –m flask run

# docker run -p 8000:5000 python-docker             //normal
# docker run -d -p 8000:5000 python-docker          //in background

# *Enter Container*
# docker exec -it $CONTAINER_NAME bash
# docker exec -it reverent_aryabhata bash

# *Stop Container*
# docker stop $CONTAINER_NAME
# docker stop reverent_aryabhata

# docker compose up

# *Create Volumes*
# docker volume create $VOLUME_NAME
# docker volume ls

# *Create Network*
# docker network create $NETWORK_NAME
# docker network ls

# *Run MySQL*
# docker run --rm -d -v mysql:/var/lib/mysql -v mysql_config:/etc/mysql -p 3316:3306 --network mysqlnet --name mysqldb -e MYSQL_ROOT_PASSWORD=test123 mysql
# *Enter Database*
# docker exec –it mysqldb mysql –u root -p

# *Get right version in requirements.txt*
# pip list | findstr mysql >> requirements.txt

# docker build -t python-docker:1.0.1 .
# docker run -d -p 5002:5000 python-docker:1.0.1

# *Run MySQL REST-SERVER*
# docker run --rm -d --network mysqlnet --name rest-server -p 8000:5000 python-docker

# docker compose up -d
# docker-compose -f docker-compose.yml up --build


#*Get image from teacher*
# docker pull ainhoaazqueta/is-cloud:1.0.0
# docker run -p 5004:5000 -d ainhoaazqueta/is-cloud:1.0.0
# "-d" is for no logs------^

