# Databases in AWS

## Choosing the right database
- We have a lot of managed databases on AWS to choose from
- Questions to choose the right databse based on your architecture
  - What is the size of the data?
  - What is the read/write ratio?
  - What is the query pattern?
  - What is the latency requirement?
  - What is the throughput requirement?
  - What is the availability requirement?
  - What is the consistency requirement?
  - What is the durability requirement?
  - What is the cost requirement?
  - ...

### Database Types

#### Relational Databases
- RDS
  Managed PostgreSQL, MySQL, MariaDB, Oracle, SQL Server, and Aurora
  Provisioned RDS Instance Size
  Auto-scaling capability for Storage
  Support for Read Replicas and Multi-AZ
  Security through IAM, Security Groups, KMS and SSL
  Automated Backups and Snapshots with Point in time restore
  Managed and Scheduled maintenance (with downtime)
  Support for IAM Authentication, integration with Secrets Manager
  RDS Custom for access to and customize the underlying instance
- Amazon Aurora
  Compatible API for 

#### NoSQL Databases
- DynamoDB
- ElastiCache  

#### Object Store
- S3

#### Data Warehouse
- Redshift
- Athena
- EMR

#### Search
- OpenSearch

#### Graphs
- Amazon Neptune

#### Ledger
- Amazon Quantum Ledger Database (QLDB)

#### Time Series
- Amazon Timestream

## RDS