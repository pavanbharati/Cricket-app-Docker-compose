# Cricket-app-Docker-compose
```
1. Launch instance (Amazon Linux) with the below user data to install Docker
#! /bin/bash
sudo -i
yum install docker -y
systemctl start docker

2. Install Docker Compose
Download Docker Compose
=> sudo curl -L "https://github.com/docker/compose/releases/download/v2.10.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

Check the File. It should indicate that it's a binary file.
=> file /usr/local/bin/docker-compose

ls /usr/local/bin/
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose

Give the permissions to execute the docker compose
sudo chmod +x /usr/local/bin/docker-compose

To check docker-compose version
docker-compose version

```
