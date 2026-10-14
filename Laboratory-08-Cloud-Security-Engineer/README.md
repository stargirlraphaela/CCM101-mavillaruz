# Laboratory Activity 8: The Cloud Security Engineer

## Mission Overview

This laboratory activity focuses on securing a Linux server using the Uncomplicated Firewall (UFW). I deployed an Nginx web server using Docker, reviewed the firewall configuration, and applied security rules to allow SSH and web application traffic while denying other incoming connections by default.

## Objectives

- Understand the Principle of Least Privilege.
- Explain the concept of an attack surface.
- Audit active network ports and services.
- Configure UFW with a Default Deny incoming policy.
- Allow SSH and TCP port 8080.
- Document firewall rules and security practices.
- Expand my GitHub Cloud Computing portfolio.

## Commands Executed

| Command | Purpose |
|---|---|
| `docker --version` | Check the Docker version. |
| `docker run -d --name secure-web-app -p 8080:80 nginx` | Deploy the Nginx container. |
| `curl http://localhost:8080` | Test the web application. |
| `sudo ufw allow ssh` | Allow SSH traffic. |
| `sudo ufw default deny incoming` | Block incoming traffic by default. |
| `sudo ufw default allow outgoing` | Allow outgoing traffic. |
| `sudo ufw enable` | Activate the firewall. |
| `sudo ufw status verbose` | Check firewall status and policies. |
| `sudo ufw allow 8080/tcp` | Allow TCP port 8080. |
| `sudo ufw status numbered` | Display numbered firewall rules. |

## Skills Learned

- Deploying a web server using Docker.
- Testing web application connectivity with curl.
- Configuring and checking UFW firewall rules.
- Applying the Default Deny security policy.
- Managing network ports and reducing the attack surface.
- Writing technical documentation using Markdown.
- Collecting screenshots as evidence for a cloud security laboratory.

