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
