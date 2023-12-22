Backup Config is a script which can be placed in /etc/cron.daily
In the configuation section the parameters BACKUP_DIR, SYSTEM, FILES, MAX_BACKUPS determine
what, where-to and how often FILES will be backed up to the target directory /var/adm/backup/$SYSTEM
Each backup is compared to the previous and the files will be backed up if changes exist.
