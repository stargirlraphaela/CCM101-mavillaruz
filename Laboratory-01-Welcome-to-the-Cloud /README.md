# Mission Overview

This laboratory activity, **Welcome to the Cloud**, introduces the fundamentals of working with a cloud-based Linux environment. The mission focuses on using the KillerCoda Linux Playground, creating and managing a user account, exploring system information, organizing files and directories, and documenting the completed activities in a GitHub repository.

The laboratory also provides hands-on experience with basic Linux commands and Markdown documentation. By completing the checkpoints, I was able to set up my Linux workspace, gather system information, create the required directory structure, and organize my laboratory outputs in a GitHub portfolio.

## Objectives

* Access and use a cloud-based Linux environment through KillerCoda.
* Explore and verify the functionality of a Linux terminal.
* Create and configure a new Linux user account with Bash, a home directory, and sudo privileges.
* Navigate the Linux file system and manage directories and files.
* Identify basic system information such as the Linux distribution, kernel version, CPU, memory, and disk space.
* Create and edit Markdown files.
* Organize laboratory activities and documentation in a GitHub repository.
* Practice documenting technical activities using Markdown.
* Capture screenshots as evidence of completed laboratory tasks.

## Activities Performed

### Checkpoint 1 – Enter the Cloud

* Launched an Ubuntu Linux Playground using KillerCoda.
* Created and logged into a new user with Bash, a home directory, and sudo privileges.
* Recorded the username, working directory, and hostname.

### Checkpoint 2 – Meet Your Environment

* Checked the Linux distribution, kernel version, CPU, memory, and disk space.
* Recorded the results in `system-information.md`.

### Checkpoint 3 – Build Your Workspace

* Created the required folder structure in the home directory.
* Created `about-me.md` inside the `Notes` folder.
* Captured a screenshot of the file in the terminal.

### Checkpoint 4 – Create Your Portfolio

* Created a public GitHub repository.
* Added the required folders, files, and laboratory documentation.

### Checkpoint 5 – Document Your Mission

* Created the laboratory `README.md` and documented the completed activities.

### Checkpoint 6 – Capture Evidence

* Created a `screenshots` folder and added the required screenshots.

### Checkpoint 7 – Complete the Mission

* Reviewed the repository, committed the changes, and pushed the final work to GitHub.

## Linux Commands Used

### Checkpoint 1

```bash
sudo useradd -m -s /bin/bash mavillaruz
sudo passwd mavillaruz
sudo usermod -aG sudo mavillaruz
su - mavillaruz
whoami
pwd
hostname
```

### Checkpoint 2

```bash
grep PRETTY_NAME /etc/os-release
uname -r
lscpu | grep "Model name"
free -h
df -h /
```

### Checkpoint 3

```bash
cd ~
mkdir -p Notes
touch Notes/about-me.md
cat Notes/about-me.md
```

### Other Commands Used

```bash
ls
cd
mkdir
touch
cat
```

## Skills Learned

Through this laboratory activity, I developed a better understanding of working with a cloud-based Linux environment. I learned how to create and manage Linux user accounts, configure user privileges, navigate directories, and create files using the terminal.

I also learned how to gather basic system information, organize files and folders, and create Markdown documentation. Additionally, I gained practical experience in creating and organizing a GitHub repository, documenting laboratory activities, and maintaining a structured portfolio.

Overall, this activity helped me improve my command-line skills, Linux fundamentals, documentation skills, and understanding of cloud-based computing environments.
