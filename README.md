# ElasticForOracle
Sync your Search engine with your data from Oracle database. 


# Getting started
 


# Installation
1. Download the Util packages
2. Connect as DBA 
```
% cd /sync_scripts
% sqlplus sys as sysdba
Enter password: password
```
3. Create Tablespace 
```
create tablespace SYNC_TS...
```
4. Create SYNC_ADMIN user
```
create user SYNC_ADMIN identified by <password> default tablespace SYNC_TS;
```
5. Grant Privileges
```
@grants.sql
```
6. Connect to SYNC_ADMIN
```
SQLPLUS> conn SYNC_ADMIN
```
7. Create SYNC_ADMIN tables
```
@create_schema.sql
```

# Create Outbound Synchronization

# Create Inbound Synchronization

# Create Extranl Index Service

# USE CASES
### Applicaiton analysis
### Oracle Performance Monitoring
### External Indexing and Text analysis



