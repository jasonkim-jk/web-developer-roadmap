# Docker
Docker is similar in concept to Virtual Machines, except it’s much more lightweight. Instead of running an entire separate operating system (which is a massive overhead), Docker runs containers, which use the same host operating system, and only virtualize at a software level.

<img src="https://images.idgesg.net/images/article/2017/06/virtualmachines-vs-containers-100727624-large.jpg">

> https://www.infoworld.com/article/3204171/what-is-docker-the-spark-for-the-container-revolution.html

> https://www.cloudsavvyit.com/490/what-does-docker-do-and-when-should-you-use-it/

## Docker Images and containers🔗
Fundamentally, a container is nothing but a running process, with some added encapsulation features applied to it in order to keep it isolated from the host and from other containers. One of the most important aspects of container isolation is that each container interacts with its own private filesystem; this filesystem is provided by a Docker image. An image includes everything needed to run an application - the code or binary, runtimes, dependencies, and any other filesystem objects required.

* https://www.docker.com/resources/what-container
* https://docs.docker.com/get-started/#images-and-containers

<img src="https://phoenixnap.com/kb/wp-content/uploads/2019/10/container-layers.png">

> https://phoenixnap.com/kb/docker-image-vs-container

## Docker Hub
Docker Hub is the world's largest
library and community for container images
* https://hub.docker.com/

<img src="https://www.javainuse.com/dock-8-11-min.JPG">

## Docker Engine
<img src="https://docs.docker.com/engine/images/engine-components-flow.png">

> https://docs.docker.com/get-started/overview/

## Installing Docker
* https://docs.docker.com/desktop/
