# Docker Compose Guide

## Docker Compose Configuration

The `docker-compose.yml` file defines the services needed for the Nextcloud deployment. It contains two services: a MariaDB database and a Nextcloud application.

## What Does the `services:` Block Do?

The `services:` block defines the containers that Docker Compose will create and manage. In this project, there are two services:

* `database` - runs the MariaDB database.
* `app` - runs the Nextcloud web application.

Docker Compose uses this configuration to create and connect the required containers.

## How did the Nextcloud app container know how to find the database container?

The Nextcloud container uses the following environment variable:

```yaml
- MYSQL_HOST=database
```

The value `database` matches the service name of the MariaDB container. Docker Compose provides networking between the services, allowing the Nextcloud application to communicate with the database using the service name.

## Environment Variables

The Compose file uses environment variables to configure the database and Nextcloud application.

For example:

```yaml
- MYSQL_PASSWORD=cloudnova_pass
- MYSQL_DATABASE=nextcloud_db
- MYSQL_USER=nextcloud_user
```

These variables provide the database credentials and database name required by the application.

## What is the difference between docker run (which you used in Mission 4) and docker-compose up -d?

`docker run` is normally used to create and start an individual container by providing its configuration directly in a command.

`docker-compose up -d` reads a Compose YAML file and creates multiple related containers according to the configuration. The `-d` option runs the containers in the background.

For example:

```bash
docker-compose up -d
```
