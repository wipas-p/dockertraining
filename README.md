# Docker Training
https://github.com/wipas-p/dockertraining <br>
<br>
Docker command <br>
============================ <br>
docker build -t {image} .  <br>
docker run -d -p 8989:80 --name {container} {image}  <br>

======= <br>
git clone https://github.com/wipas-p/dockertraining.git <br>

docker build -t web-red .  <br>
docker run -d -p 8001:80 --name webred web-red  <br>

docker build -t web-green .  <br>
docker run -d -p 8002:80 --name webgreen web-green <br>

<br>
docker image ls <br>
docker container ls <br>

docker stop {container-name} <br>
docker rmi {image:tag} <br>


