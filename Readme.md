## Use Python to Create a WordPress Backup

* upload the wpbackup file to the WordPress install that you want to backups
* I recommend placing this just outside the website root or public directory
* run the "python wpbackup" command.

## How to run
```shell
$ python wpbackup
```

Assumptions

The WordPress Installation is in the public directory
wp-content is in the public directory website root
Python 2.7 is installed

backups will be saved in 'public/wp-content/py-backup'
we will attempt to create the dir if it does not exist
you can change this by updating the backup_dir var
sitename var should be updated to match your website
