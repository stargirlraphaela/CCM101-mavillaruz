# Mission Reflection

Throughout this semester, I learned that cloud computing involves more than just creating virtual machines or running applications. It also includes managing resources, protecting systems, monitoring performance, storing data, and automating repetitive tasks. This laboratory helped me understand how automation can make cloud operations more efficient and reliable.

Automation is critical when managing hundreds of cloud servers because performing the same task manually on every server takes too much time and can lead to human errors. With Bash scripts and Cron jobs, administrators can schedule tasks such as backups and maintenance to run automatically. This saves time and helps ensure that important tasks are performed consistently.

However, automation also has potential dangers. If a script contains a destructive command or an incorrect file path, it could delete important data or damage many servers if executed across 1,000 machines. To reduce these risks, scripts should be tested in a safe environment, reviewed carefully, and given only the permissions they need. Administrators should also maintain backups and monitor automated tasks.

Writing a Bash script was different from creating a Docker Compose YAML file in Mission 6. Bash uses commands and variables to perform tasks step by step, while Docker Compose uses YAML to describe services, networks, and other application settings. Bash focuses on executing instructions, whereas Docker Compose focuses on defining how containers work together.

From Laboratory 1 to Laboratory 9, my understanding of cloud computing has grown from learning basic concepts to working with infrastructure, multi-cloud platforms, containers, storage, monitoring, security, and automation. I now understand that these areas work together to support reliable cloud environments.
