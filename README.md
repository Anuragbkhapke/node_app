# node-todo-cicd

Run these commands for run on local server on ubuntu:


`sudo apt install nodejs`


`sudo apt install npm`


`npm install`

`node app.js`

# Run your application by docker follow this commands 

update ubuntu sysytem using this command
`sudo apt update`


install docker using command  
`sudo apt-get install docker.io -y`


buid docker image from docker file 
`docker build -t node:v1 .`


run docker container  from docker image
`docker run -d -p 8000:8000 --name nodec node:v1`


see the runing container on docker
`docker ps`

or Run using docker compose 


install docker compose on ubuntu
`sudo apt-get install docker-compose -y`


run the application using docker compose
`docker-compose up -d`


access application on your computer browser using ec2 public ip 
`http://<public_ip>:8000`
