# Docker image shipping using github actions

## 15 most used docker commands

1. docker pull nginx
- pull nginx image from docker hub registry to local machine
![command1](screenshots/command1.PNG)

2. docker images
- To check the list of images pulled from the dockerhub registry
![command2](screenshots/command2.PNG)
3. docker run -d --name container_nginx -p 8000:80 nginx
- To run nginx docker image in detached mode
![command3](screenshots/command3.PNG)
4. docker ps
- To see the current list of running containers and running ports
![command4](screenshots/command4.PNG)
![command4_run](screenshots/command4_running.PNG)

5. docker stop 1d1b7
- To stop the container that is up and running
![command5](screenshots/command5.PNG)

6. docker ps -a
- To get the history of containers that are exited as well as up and running
![command6](screenshots/command6.PNG)
 
 7. docker login
 - To login to user owned dockerhub
![command7](screenshots/command7.PNG)

8. docker kill b924
- force shutdown of the container with id=b924
![command8](screenshots/command8.PNG)

9.  docker rm b924
- To remove container with id=b924

**Before**
![command9_before](screenshots/command9_before.PNG)
**After**
![command9_after](screenshots/command9_after.PNG)

10. docker rm $(docker ps -a -q)
- remove a particular container with id=df88
![command10](screenshots/command10.PNG)

11. docker rmi nginx
- remove a specified image
![command11](screenshots/command11.PNG)

12. docker rm $(docker ps -a -q)
- remove all the containers present in the machine
![command12](screenshots/command12.PNG)

13. docker rmi $(docker images -a)
- remove all the images present in the machine
![command13](screenshots/command13.PNG)

14. docker build -t myimage .
- building a docker image

15. docker push abhishekvarma979/app:latest
- pushing the built image to the docker registry

## Task2:

### Run the hello-world image
![helloworld image running](screenshots/helloworld.PNG)

