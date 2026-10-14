# Backup Script Guide

## Backup Script

```bash
#!/bin/bash

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

mkdir -p "$BACKUP_DIR"
tar -czf "$BACKUP_DIR/backup_$TIMESTAMP.tar.gz" "$SOURCE_DIR"

echo "Backup completed successfully at $TIMESTAMP!"
```

## File Permissions

The command `chmod +x backup.sh` gives the script permission to execute, allowing it to run as a program.

## Cron Job

```cron
0 2 * * * /root/backup.sh
```

| Time Field | Value | Meaning |
|---|---|---|
| Minute | `0` | At minute 0 |
| Hour | `2` | At 2:00 AM |
| Day of Month | `*` | Every day of the month |
| Month | `*` | Every month |
| Day of Week | `*` | Every day of the week |

This cron job runs the backup script automatically every day at 2:00 AM.
