# Linux SysAdmin Showcase
My Rocky Linux server configuration and system administration practices.  
This repository tracks my Linux system configurations, monitoring scripts, and automation tools. It's a collection of the configs and scripts I use to manage and secure my Rocky Linux server.  

## Structure
```
├── etc/          # System configuration files
├── scripts/      # Automation and utility scripts
├── systemd/      # Custom systemd services
└── watch/        # Symlinks to files I monitor daily
    ├── logs/
    ├── configs/
    └── status/
```

## What I Monitor
I keep an eye on these logs for security and system health:

- **Security**  :  `/var/log/secure`   - login attempts, authentication
- **System**    :  `/var/log/messages` - general system events
- **Audit**     :  `/var/log/audit/`   - SELinux and security events
- **Tasks**     :  `/var/log/cron`     - scheduled jobs

## About
This is my working system admin repository. I add configs and scripts as I discover and create them.
