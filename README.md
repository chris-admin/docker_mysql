## Backup example
```
docker exec db /usr/bin/mysqldump -u root --password=my_secret_password --all-databases --result-file=/data/dbbackup/backup.sql
```