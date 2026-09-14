# Mission Reflection

This laboratory helped me understand how containers can make application deployment faster and easier compared to Virtual Machines. When using a Virtual Machine, I need to create the virtual machine, install an operating system, configure it, and then install the required applications. This process can take several minutes and requires more RAM and storage. In comparison, a Docker container can start in seconds because it uses the host operating system kernel and does not need a complete operating system inside the container.

The port mapping `-p 8080:80` is necessary because the Nginx web server is running on port 80 inside the container. Port 8080 on the host is connected to port 80 in the container, allowing me to access the Nginx website through `http://localhost:8080`. Without this port mapping, I would not be able to easily access the web server from the host using port 8080.

I also learned what happens when using the `docker rm` command. It removes the container from Docker after the container has been stopped. Any data stored only inside the container can be lost when the container is removed. This shows why persistent data should be stored using volumes or other external storage when necessary.

Containerization can also improve the way developers and IT operations teams work together. Developers can package an application and its dependencies into a container, while operations teams can deploy the same container in different environments. This supports the DevOps approach because development and operations can work with the same application environment.

Finally, my GitHub portfolio is becoming more organized and complete. Each laboratory adds new documentation, commands, screenshots, and reflections. This activity added Docker and containerization skills to my portfolio and helped me understand an important part of cloud-native computing.
