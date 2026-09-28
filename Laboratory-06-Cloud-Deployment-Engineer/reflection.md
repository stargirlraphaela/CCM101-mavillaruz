# Mission Reflection

Writing a `docker-compose.yml` file makes a cloud engineer's job easier because the configuration for multiple services can be written in one place. Instead of manually typing several Docker commands, the engineer can use `docker-compose up -d` to deploy the complete application. The same configuration can also be reused when the application needs to be deployed again.

YAML indentation is very important because YAML uses spaces to define the structure of the configuration. If I make an indentation error or use a Tab instead of spaces, Docker Compose may not understand the file correctly and can return an error. This means that I need to carefully check the spacing and structure of the YAML file before deploying it.

Environment variables such as `MYSQL_PASSWORD` are used to provide configuration values to the containers. They allow the application and database to know important information such as usernames, passwords, database names, and hostnames. In this activity, the environment variables helped connect the Nextcloud application to the MariaDB database.

It was interesting to see a complete cloud storage application become available after only a few commands. Docker Compose handled the creation and connection of the Nextcloud and MariaDB containers, which showed me how Infrastructure as Code can simplify cloud deployment.

My understanding of Cloud Computing has developed since Mission 1. I started by learning basic cloud concepts and working with Linux commands. Later, I learned about infrastructure, containers, object storage, and now multi-container deployments. I now understand that cloud computing is not only about storing data or running applications. It also involves designing, deploying, connecting, managing, and documenting different services so they can work together as one system.
