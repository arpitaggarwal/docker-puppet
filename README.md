# docker-puppet

### Steps to launch and start docker-puppet app

**Step 1 :** Launch Docker Quickstart Terminal.

**Step 2 :** Build Docker container using command `docker build --no-cache=true -t spring-application-container .`

**Step 3 :** Start Docker container using command `docker run -p 8080:8080 --cap-add SYS_PTRACE -it spring-application-container /bin/bash`


#### Difference between a Docker Image and a Docker Container?

Difference is same as that of difference between a Java Class and an Object. In practice, Object is the runtime instance of a Class. Similarly, Container is the runtime instance of an Image.

Object gets created only once it is instantiated. Similarly Container can be running or stopped. And containers are created out of an image, though this might not be the case always.


### Docker Commands

1. List Docker images - `docker images`

2. List running Docker container - `docker ps`

3. List all containers - `docker ps -a`

4. List latest created containers - `docker ps -l`
