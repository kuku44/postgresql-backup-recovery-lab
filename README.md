# postgresql-backup-recovery-lab
PostgreSQL Backup, Point-in-Time Recovery, and Streaming Replication.
# PostgreSQL Backup, Recovery, and Replication Lab

## Objective
To learn how to back up PostgreSQL databases, configure WAL archiving, perform point-in-time recovery (PITR), and establish streaming replication.

## Tools Used
- PostgreSQL 16
- SQL and psql
- Windows PowerShell
- pg_dump and pg_restore
- pg_basebackup

## Practical Activities

### 1. Database Backup
Practiced PostgreSQL database backup and restoration.

### 2. WAL Archiving
Configured WAL archiving and checked archive statistics.

### 3. Streaming Replication
Configured a primary PostgreSQL server and a standby server.

### 4. Replication Verification
Verified that changes made on the primary database appeared on the standby server.

### 5. Point-in-Time Recovery (PITR)
Status: Completed and verified.

- Created a separate PITR test database.
- Configured WAL restoration.
- Created a named restore point: `pitr_before_change`.
- Recovered the database to the named restore point.
- Verified that the record inserted after the restore point was excluded.

Evidence: `pitr-verification.png`

## Evidence
Screenshots and practical results will be added to the screenshots folder.

## Conclusion
This lab helped me understand PostgreSQL database backup, WAL archiving, streaming replication, and disaster recovery.
