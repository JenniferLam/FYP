GitHub
Username: tcpsawingting@gmail.com
Password: Jennifer123


Microsoft SQL Server 2017
Instance Name: FYPSQL
Password: Jennifer123
Configuration please refer to the screenshots

Jupyter Notebook
- type jupyter notebook in cmd

Oracle DB
SID: fypDB
Password: fyp123
see screenshot for configuration details

DB administrator A/C
Username: SYSTEM
Password: fyp123

Connect to DB:
Connection Name: fypDB
User account:
User name: developer
Password: Passw0rd123


To check all tables owned by someone, 
SELECT
  table_name, owner
FROM
  all_tables
ORDER BY
  owner, table_name

or 

SELECT
  table_name, owner
FROM
  all_tables
where owner='developer';
ORDER BY
  owner, table_name




