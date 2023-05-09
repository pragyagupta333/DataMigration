# Data Migration

Data migration is the process of moving stored digital information between computers, systems, or formats

In this repository I have **Migrated 10 Tables**  with all constraints and data from [**PostgreSQL**](https://www.postgresqltutorial.com/) To [**Microsoft SQL Server**](https://www.sqlservertutorial.net/)
## Dataset Used 
[Sample Database](https://www.databasestar.com/sample-database-superheroes/)      - [**Download**](https://github.com/pragyagupta333/DataMigration)

![l_DM](https://user-images.githubusercontent.com/125549428/237056337-f610ea3a-706f-482f-9aec-c1229ffab925.png)


## Tools And Technologies
- [ESF Migration Tool](https://www.dbsofts.com/download/)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

## Demo
- Step 1 : Choose A Source Database (Here, In PostgreSQL)
    - This database will have all the tables you want to migrate
   
   ![a_DM](https://user-images.githubusercontent.com/125549428/237061289-68365363-5916-47a7-a4db-20250911b4c0.png)![b_DM](https://user-images.githubusercontent.com/125549428/237061547-1f12cd54-69bc-425e-a08f-60327a68487f.png)
   
 - Step 2 : Choose Your Destination Database (Here, SQL Server)
      - Note : It is currently empty
   
   ![c_DM](https://user-images.githubusercontent.com/125549428/237062204-a948f854-49dc-475a-bfee-a8f08fc0a66f.png)

- Step 3 : Launch ESF Migration Tool
    
    ![d_DM](https://github.com/pragyagupta333/DataMigration/assets/125549428/7584ac26-bd60-4ae5-a15c-af89baef7250)



- Step 4 : Choose Your Source, Server,Username,etc as shown below or as needed
    - Click on Refresh To choose Your Database
    - Carefully choose schema if tables are in schema other than default schema (public).
    - Click on "Next"

  ![e_DM](https://github.com/pragyagupta333/DataMigration/assets/125549428/77c9ffd8-ab60-4308-95f2-7b4c92ffa118)
- Step 5 : Choose Your Destination, Server name,etc as shown or as needed

    ![f_DM](https://github.com/pragyagupta333/DataMigration/assets/125549428/84e5dcde-5ffa-4733-9cbd-4800c1fc58ba)

- Step 6 : Select Tables You want To migrate

    ![g_DM](https://github.com/pragyagupta333/DataMigration/assets/125549428/dc85bb8f-8493-40f2-abd1-20498ffede7e) 

- Step 7 : Click On Submit And Wait

    ![h_DM](https://github.com/pragyagupta333/DataMigration/assets/125549428/f222fdc5-244e-49a1-a89e-d24d5199c8c9) ![i_DM](https://github.com/pragyagupta333/DataMigration/assets/125549428/86d26a06-bdb6-42e9-9932-0f356a70f097)
    
- Step 8 : Click On Exit Once it Finishes.
    - Note : No Errors Occured And Migration Was Successfull
   
    ![j_DM](https://github.com/pragyagupta333/DataMigration/assets/125549428/8109f397-85ae-4ca2-835a-0a564c69ee53)

- Step 9 : View Your Tables in Destination Database 
  - Note : All 10 Tables Are Migrated And Are Visible

![k_DM](https://github.com/pragyagupta333/DataMigration/assets/125549428/4cf6cc2d-b92a-4cf4-9154-54abf274368c)

Outcomes : One Of The Migrated Table With Data.

   ![m_Dm](https://github.com/pragyagupta333/DataMigration/assets/125549428/ce638212-c3b4-4e7e-b03c-77cd855c988b)


## References

 - [Database Star](https://www.databasestar.com/sample-database-superheroes/)
 - [Dataset Source](https://github.com/bbrumm/databasestar/tree/main/sample_databases/sample_db_superheroes)     
-  [ESF Migration Tool](https://www.dbsofts.com/)
