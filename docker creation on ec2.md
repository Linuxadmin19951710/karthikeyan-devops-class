![app](https://github.com/user-attachments/assets/dd9358df-b690-4595-9820-0acccbe5ee72)
![ec2 instance](https://github.com/user-attachments/assets/41167101-ea89-4192-80c1-8db1224a309e)
![docker images](https://github.com/user-attachments/assets/775c71a9-12d0-4978-b394-79d50582791d)
![docker images commands](https://github.com/user-attachments/assets/99cb5174-7ed8-45e4-86d1-4f308b78ab2f)
![docker conatiner commands1](https://github.com/user-attachments/assets/eb3f2423-ccbc-4741-b59e-f605fefc64e7)
![docker conatiner commands2](https://github.com/user-attachments/assets/33ccdf11-55b9-4d4a-9964-b09c96ac5e8c)
![docker indx file](https://github.com/user-attachments/assets/51a78ac0-0afe-4777-8426-22caf579bf74)
![docker network commands](https://github.com/user-attachments/assets/e8e7ead9-48b6-46f8-8681-b1c8911c2c0e)
![docker version](https://github.com/user-attachments/assets/ab30caef-5785-4c16-8abd-26bf1b6952c9)

 
 sudo apt update
 sudo apt-get install apt-transport-https ca-certificates curl software-properties-common
 curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
 sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu  $(lsb_release -cs)  stable"
 sudo apt update
 sudo apt-get install docker-ce
 docker --version
 
root@ip-172-31-5-178:~# docker --version
Docker version 27.3.1, build ce12230
root@ip-172-31-5-178:~#

mkdir myapp
cd myapp ~
echo "Hello, world!" ＞ index.html
touch Dockerfile
vim Dockerfile
docker build -t myapp .
systemctl status nginx
apt install nginx
systemctl status nginx
docker build -t myapp .
vi Dockerfile
docker build -t myapp .
docker images
docker run -p 8080:80 myapp
docker run -d -p 8080:80 myapp
docker ps

docker ps -a
docker ps
docker diff 47129c0ad63a
docker top 47129c0ad63a
docker inspect 47129c0ad63a
docker ps
docker logs 47129c0ad63a
docker stats 47129c0ad63a

docker images ls
docker images
docker history myapp
docker inspect myapp
docker ps
docker run -d 47129c0ad63a
docker network ls
docker network connect 0ae965ff1ca1 47129c0ad63a
docker network disconnect 0ae965ff1ca1 47129c0ad63a
docker stop 47129c0ad63a
docker network inspect 0ae965ff1ca1
cat index.html
cd myapp
cat index.html
root@ip-172-31-5-178:~/myapp# docker stop 47129c0ad63a
47129c0ad63a
root@ip-172-31-5-178:~/myapp#





