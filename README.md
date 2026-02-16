Oracle Pluggable Database Management – Assignment II

Student: NGANJI BIREZI CHRISTELLE

Student ID: 29011

Course: INSY 8311 Database Development with PL/SQL  

Overview
This assignment demonstrates hands-on Oracle Multitenant architecture skills by creating, managing, and deleting Pluggable Databases (PDBs) in Oracle 21c. The environment simulates a banking infrastructure where isolated PDBs will host future customer and transaction systems.

 Oracle Environment
- Database: Oracle 21c Enterprise Edition  
- Client Tool: SQL*Plus, SQL Developer Extension (VS Code)  
- OS: Windows 11  
- OEM Port: 5500 (HTTPS)

 Task Execution

Task 1: Permanent PDB Creation
- Created PDB: ch_pdb_29011
  ![Description](screenshots/creating_a_pluggable_database.png)
)
- Created user: christelle_plsqlauca_29011 with DBA privileges
  ![Description](screenshots/creation_of_user.png)
- PDB is open and ready for application deployment
  ![Description](screenshots/opening_pluggable_database.png
)

Task 2: Temporary PDB Lifecycle
- Created: ch_to_delete_pdb_29011
   ![Description](screenshots/creation_of_temporary_database.png)
- Verified existence
  ![Description](screenshots/verifying_if_temporary_db_is_created.png
)
- Dropped with INCLUDING DATAFILES
  ![Description](screenshots/deleting_the_temporary_database.png)
- Confirmed removal
   ![Description](screenshots/confrimation_of_deletion_of_temporary_database.png
)
![Description](screenshots/creation_of_user.png)
Task 3: Oracle Enterprise Manager
- OEM Express enabled on port 5500
   ![Description](screenshots/loging_in.png) 
- Dashboard confirms PDB status and environment health
  ![Description](users.png)

 Challenges & Solutions

- Challenge: PDB not opening after creation  
  Solution: Ran ALTER PLUGGABLE DATABASE ... OPEN; explicitly

Integrity Statement
All commands were executed personally on my local Oracle 21c instance. Screenshots reflect my own terminal and OEM sessions. No AI tools were used to generate commands or solutions.

 Submission Info
- PDB Name Created: ch_pdb_29011  
- Issues Encountered: Yes (resolved as above)
