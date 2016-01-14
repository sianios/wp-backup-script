================
wp-backup-script
================

A simple script to backup wordpress database and website root directory weekly.

Requirements
------------
* Debian or Ubuntu
* mailutils package

Install
-------
Edit backup and set variables DIR, SITE_NAME, DEST_DIR and MAIL (optional). Explanation of
variables in file.
Move backup file to /etc/cron.weekly/ or just execute the command bellow.
```bash
sudo cp backup /etc/cron.weekly/
```

About
-----
https://github.com/sianios/wp-backup-script
