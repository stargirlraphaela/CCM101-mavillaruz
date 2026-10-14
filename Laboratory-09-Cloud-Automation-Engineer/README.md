# Laboratory 09: The Cloud Automation Engineer

## Mission Overview

This laboratory focuses on automating repetitive cloud administration tasks using Bash scripting and the Linux Cron scheduler. I created a sample application data directory, wrote a script to compress the data into a backup archive, and configured a cron job to schedule automatic backups.

## Objectives

- Understand the basic syntax of Bash scripts.
- Create and execute a backup script using Nano.
- Modify file permissions using `chmod`.
- Create compressed backup archives using `tar`.
- Configure and verify a scheduled task using `crontab`.
- Document automation procedures using Markdown.

## Commands Executed

| Command | Purpose |
|---|---|
| `mkdir -p app-data` | Creates the application data directory. |
| `echo "This is critical client data." > app-data/data.txt` | Creates a sample data file. |
| `nano backup.sh` | Creates or edits the Bash script. |
| `./backup.sh` | Executes the backup script. |
| `chmod +x backup.sh` | Grants execute permission. |
| `ls -l backups/` | Lists the generated backup files. |
| `tar -tzf backups/backup_*.tar.gz` | Lists archive contents. |
| `crontab -l` | Displays scheduled cron jobs. |
| `env EDITOR=nano crontab -e` | Opens the cron table for editing. |

## Skills Learned

- Bash shell scripting and variable usage.
- Creating and compressing backup archives.
- Linux file permissions and executable scripts.
- Scheduling recurring tasks using Cron.
- Writing technical documentation in Markdown.
- Organizing and maintaining a GitHub Cloud Computing portfolio.
