# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

In this laboratory activity, I used Docker Compose to deploy a multi-tier private cloud storage application. The application consisted of a Nextcloud web container and a MariaDB database container.

## Objectives

* Explain two-tier application architecture.
* Create a Docker Compose YAML configuration.
* Use the Linux `nano` text editor.
* Deploy multiple containers using Docker Compose.
* Access Nextcloud through a web browser.
* Practice Infrastructure as Code principles.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```

## Skills Learned

* Understanding multi-tier architecture.
* Writing YAML configuration files.
* Using Docker Compose.
* Deploying multiple containers together.
* Connecting application and database containers.
* Using environment variables.
* Managing cloud infrastructure through Infrastructure as Code.
