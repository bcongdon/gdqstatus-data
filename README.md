# gdqstatus-data
Database backups from GDQStat.us

## Explanation

- Each file is a ZIP file of a Postgres database dump. You can setup a Postgres DB and use `pg_restore` to load in the data from the backup.

- Each backup file is independent. For example, `agdq_2018_final_db.zip` contains data from *only* AGDQ 2018.

