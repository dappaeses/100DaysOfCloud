
## Cloud Research
### AWS RDS
• RDS stands for Relational Database Service

• It’s a managed DB service for DB use SQL as a query language.

• It allows you to create databases in the cloud that are managed by AWS

    • Postgres
    • MySQL
    • MariaDB
    • Oracle
    • Microsoft SQL Server
    • Aurora (AWS Proprietary database)

### Advantage over using RDS versus deploying DB on EC2
• RDS is a managed service:

    • Automated provisioning, OS patching
    • Continuous backups and restore to specific timestamp (Point in Time Restore)!
    • Monitoring dashboards
    • Read replicas for improved read performance
    • Multi AZ setup for DR (Disaster Recovery)
    • Maintenance windows for upgrades
    • Scaling capability (vertical and horizontal)
    • Storage backed by EBS (gp2 or io1)
    
• BUT you can’t SSH into your instances

### Amazon Aurora

• Aurora is a proprietary technology from AWS (not open sourced)

• PostgreSQL and MySQL are both supported as Aurora DB

• Aurora is “AWS cloud optimized” and claims 5x performance improvement over MySQL on RDS, over 3x the performance of Postgres on RDS

• Aurora storage automatically grows in increments of 10GB, up to 64 TB.

• Aurora costs more than RDS (20% more) – but is more efficient

• Not in the free tier

### RDS Deployments: Read Replicas, Multi-AZ
• Read Replicas:

       • Scale the read workload of your DB
       • Can create up to 5 Read Replicas
       • Data is only written to the main DB
       
       ![image](https://user-images.githubusercontent.com/121011336/220811491-6f78bfb8-1859-46ef-bb10-2544a10b4286.png)
• Multi-AZ:

        • Failover in case of AZ outage (high availability)
        • Data is only read/written to the main database
        • Can only have 1 other AZ as failover
![image](https://user-images.githubusercontent.com/121011336/220811544-2450fc33-9808-45a3-8b07-36b708d6ae61.png)



