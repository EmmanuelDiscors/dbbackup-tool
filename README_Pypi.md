# Package dbbackup to manage server databases backups:
- Mysql: this release
- PostgreSQL: next release
- Other: futures releases

Installation:
- python -m pip install dbbackup

Configuration:
- ajust .env to match your local configration

- To logging on smtp, rename and adjust:
loggin_config_example.yaml
to: 
loggin_config.yaml

- To backup Mysql databases, rename and adjust:
mysql-backup-script.config_example.config
to: 
mysql-backup-script.config.config

Work with it:
- python
- import dbbackup
- from dbbackup import check_dbbackup

