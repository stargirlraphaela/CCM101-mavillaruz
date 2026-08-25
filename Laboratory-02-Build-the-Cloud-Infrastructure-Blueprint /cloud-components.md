# Cloud Infrastructure Components

The following cloud infrastructure components were identified from the Linux environment provided by the KillerCoda Playground. These components work together to provide the computing environment needed to run applications and services.

## 1. Compute Resources

**Purpose:**
Compute resources provide the processing power required to run applications, execute commands, and perform calculations. In cloud environments, compute resources can include virtual machines, virtual CPUs, GPUs, containers, and serverless functions.

**Importance in Cloud Computing:**
Compute resources are important because they allow organizations to run applications and services without purchasing and maintaining physical servers. Cloud providers can also scale compute resources based on workload and demand.

**KillerCoda Linux Environment:**
The KillerCoda server has an **Intel Xeon E312xx (Sandy Bridge, IBRS update)** CPU with **1 CPU core**. This CPU provides the processing power used by the Ubuntu Linux environment to execute commands and run applications.

## 2. Storage Resources

**Purpose:**
Storage resources provide space for operating system files, applications, configurations, and other data. Cloud storage can be provided through different storage types, such as object storage, block storage, and file storage.

**Importance in Cloud Computing:**
Storage is important because cloud applications need reliable space to store and access data. Cloud storage can also be expanded when additional capacity is needed and can support data availability and backup requirements.

**KillerCoda Linux Environment:**
The KillerCoda server has a **19 GiB root disk**, with `/dev/vda1` mounted at `/`. It also contains additional mounted file systems such as `/boot`, `/boot/efi`, `/run`, `/dev/shm`, and `/run/lock`. These file systems provide storage and system resources required for the Linux operating system.

## 3. Networking Resources

**Purpose:**
Networking resources provide communication between users, applications, servers, storage systems, and other cloud resources. They include IP addresses, virtual networks, routers, firewalls, load balancers, and Internet gateways.

**Importance in Cloud Computing:**
Networking is important because cloud services need reliable and secure communication. A properly configured network allows users to access applications and enables different cloud resources to communicate with each other.

**KillerCoda Linux Environment:**
The KillerCoda Linux server has the IP addresses **172.30.1.2** and **172.17.0.1**. These addresses identify network interfaces within the environment and allow the server and its services to communicate with other systems.

## 4. Operating System

**Purpose:**
The operating system manages the computer's hardware and software resources. It provides the environment where applications and commands can run and allows users and administrators to interact with the system.

**Importance in Cloud Computing:**
An operating system is important because cloud applications and services need a stable environment in which to operate. Linux is widely used in cloud computing because it is flexible, efficient, and supports many cloud, container, automation, and server technologies.

**KillerCoda Linux Environment:**
The KillerCoda server is running **Ubuntu 24.04.4 LTS** with the **6.8.0-138-generic** Linux kernel. Ubuntu manages the server's CPU, memory, storage, networking, and applications while providing the terminal environment used during this laboratory activity.
