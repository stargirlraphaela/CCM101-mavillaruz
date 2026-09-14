# Laboratory 04 – The Cloud-Native Engineer

## Mission Overview

This laboratory activity introduces containerization and Docker. The activity compares Virtual Machines and containers and demonstrates how Docker can be used to deploy an Nginx web server quickly. The Nginx container was deployed using the KillerCoda Linux environment.

## Objectives

* Understand the difference between Virtual Machines and containers.
* Verify that Docker is installed and running.
* Pull a Docker image.
* Run an Nginx container.
* Map a host port to a container port.
* Test a containerized web server.
* Manage the container lifecycle.
* Document Docker operations using Markdown.

## Docker Commands Executed

### Check Docker Installation

```bash
docker --version
```

### Check Docker Environment

```bash
docker info
```

### Download Nginx

```bash
docker pull nginx
```

### Run Nginx

```bash
docker run -d -p 8080:80 --name nginx-server nginx
```

### Test Nginx

```bash
curl http://localhost:8080
```

### List Running Containers

```bash
docker ps
```

### Stop the Container

```bash
docker stop nginx-server
```

### View All Containers

```bash
docker ps -a
```

### Remove the Container

```bash
docker rm nginx-server
```

## Skills Learned

During this laboratory, I learned how to use basic Docker commands in a Linux environment. I learned how to download images, create and run containers, map network ports, test a web server, and manage the container lifecycle. I also learned how containers can use fewer resources and start faster than traditional Virtual Machines.

## Challenges Encountered

One challenge was understanding the difference between the host port and the container port when using port mapping. I also had to make sure that the Docker commands were executed in the correct order. Testing the Nginx server with `curl` helped confirm that the container was working correctly.

