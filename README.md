# Node-Docker

## A basic nodejs application deployed using Docker. Built to practice Docker image creation and deployement.

## Stack used: 
**NodeJs** \
**ExpressJs with twilio** \
**Docker** \

## Steps to create a docker image
**1)** Create a file named "Dockerfile" in the main project directory
**2)** Add the commands in the Docker file
**3)** Open terminal and Run: docker build -t [image name]:[version] .
**Note:** Do not forget to add the dot in the above command as it is the location of the docker file.
**4)** Then check if image is created using "docker images" command

## Steps to run: 
**1)** Open the codespace and fire the terminal \
**2)** Run: Docker images \
**3)** Run: docker run -d -p 3000:3000 node-docker:1.0 \
**4)** This will start the application on LocalHost 3000 port as mentioned in previous command. \
**Note:** You can choose any local host port to run the application. \
