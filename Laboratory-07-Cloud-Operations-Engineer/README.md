# Laboratory 07: Cloud Operations Engineer

## Mission Overview

This activity focuses on monitoring a Linux server and a Docker container using KillerCoda. I checked system resources, deployed an Nginx web server, generated HTTP requests, and monitored application logs and container metrics.

## Objectives

- Monitor RAM, disk storage, and CPU usage.
- Deploy an Nginx container using Docker.
- Generate successful HTTP requests and a 404 error.
- Check application logs and container metrics.

## Monitoring Commands Executed

| Command | Purpose |
|---|---|
| `free -h` | Check RAM usage. |
| `df -h /` | Check disk storage. |
| `top` | Monitor CPU and running processes. |
| `docker run -d --name client-website -p 8080:80 nginx` | Deploy Nginx. |
| `curl -i http://localhost:8080/` | Test the web server. |
| `curl -i http://localhost:8080/hidden-admin-page` | Generate a 404 error. |
| `docker logs client-website` | View application logs. |
| `docker stats` | Monitor container resources. |

## Skills Learned

- Linux system monitoring
- Docker container deployment
- HTTP request testing
- Application log analysis
- Container performance monitoring
