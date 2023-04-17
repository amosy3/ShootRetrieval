# ShootRetrieval
Given a question in hebrew, find the most similar question from a file


## Installation 
### Install Docker
- ```sudo apt  install docker.io```
- ```sudo groupadd docker```
- ```sudo usermod -aG docker $USER```
- ```newgrp docker```
### Pull and run the docker image
- ```docker pull amosy3/shoot:0.1```
- ```docker run --rm -it -v $(pwd):/data:rw --name shoot amosy3/shoot:0.1```
