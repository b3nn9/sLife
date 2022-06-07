# 시놀로지 NAS DS218에 도커 설치
- 참고: [스택오버플로우 답변](https://stackoverflow.com/questions/52520008/can-i-install-docker-on-arm8-based-synology-nas), [tar 사용방법](https://www.happyjung.com/lecture/16), [Packages for Synology NAS](https://synocommunity.com/), [How to install IPKG on Synology NAS](https://community.synology.com/enu/forum/1/post/127148)  
- [도커 다운로드](https://download.docker.com/linux/static/stable/aarch64/)  
## 도커 설치
~~~
sudo wget https://download.docker.com/linux/static/stable/aarch64/docker-20.10.17.tgz
tar xvf docker-20.10.17.tgz
sudo tar xvf docker-20.10.17.tgz
sudo cp docker* /usr/bin/
sudo mkdir /etc/docker
sudo vi /etc/docker/daemon.json
sudo dockerd &
sudo docker run -d --network=host portainer/portainer:linux-arm64

sudo mv docker-20.10.17.tgz /volume1/docker/
~~~
