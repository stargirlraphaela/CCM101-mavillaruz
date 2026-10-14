# Mission Reflection

Completing this laboratory activity helped me understand the importance of protecting a server from unauthorized access. I learned that running an application successfully does not automatically mean that the server is secure.

A host-based firewall protects a server by controlling incoming and outgoing network traffic directly on the machine. Even if an external network security layer is breached, the firewall can still block unauthorized connections based on its configured rules. This provides another layer of protection and helps prevent attackers from accessing services they do not need.

Managing open network ports is also important because every unnecessary open port can create another possible entry point for attackers. By allowing only the required ports, such as port 22 for SSH and port 8080 for the web application, administrators can reduce the server's attack surface. The Default Deny policy makes this easier because incoming traffic is blocked unless it is specifically permitted.

In a real enterprise environment, leaving a database port such as 3306 for MySQL open to the public internet is dangerous. Attackers could attempt to guess passwords, exploit database vulnerabilities, or access sensitive information. Database access should normally be restricted to trusted application servers or private networks, with proper authentication and other security controls.

This mission also changed my perspective on how easily a server can become vulnerable. Before this activity, I mainly focused on making applications run correctly. Now, I understand that checking services, configuring firewall rules, and limiting access are also essential parts of deployment. I also learned that Docker networking must be considered when verifying firewall protection.
