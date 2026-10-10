# Mission Reflection

Checking the host server's resources is important even if containers are running perfectly because containers depend on the host's CPU, memory, and disk storage. If the server runs out of resources, applications may become slow or stop working.

The `docker logs` command helps troubleshoot login problems by showing application events and errors. These logs can help identify failed requests or other problems that need further investigation.

Monitoring logs and metrics has different purposes. Logs show individual events, requests, and errors, such as an HTTP 404 response. Metrics show numerical information about performance, such as CPU usage and memory consumption.

Large companies can use tools such as Prometheus and Grafana to monitor thousands of containers. Prometheus collects and stores performance metrics, while Grafana displays the information in dashboards and graphs. These tools help engineers identify problems and monitor system health.

This activity improved my ability to troubleshoot Linux environments by teaching me how to check RAM and disk space, monitor running processes, deploy Docker containers, and test a web server. I also learned how to examine application logs and monitor CPU and memory usage. These skills helped me understand why monitoring is important for maintaining reliable cloud applications.
