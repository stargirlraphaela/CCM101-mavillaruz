# Firewall Configuration

## Allow SSH
```bash
sudo ufw allow ssh
```

## Set Default Deny Policy
```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing
```

## Allow Port 8080
```bash
sudo ufw allow 8080/tcp
```

## What would happen if you ran sudo ufw enable before running sudo ufw allow ssh?
If I run `sudo ufw enable` before `sudo ufw allow ssh`, I may lose remote SSH access because incoming SSH connections could be blocked by the firewall.
