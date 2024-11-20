# DB_Backup_Restore

[Brief Objective]

##Project Overview

This project explores the process of manually backing up and restoring databases in SQL Server Management Studio (SSMS). We'll cover:
-	Manual Database Backup: Learn how to create database backups in SSMS.
-	Database Restore: Discover how to restore database backups to their original location or a new database.
The goal is to provide a clear and concise guide to help you master these essential database management tasks.

[Tools Used]

-	SQL Server Management Studio
  
[Getting Started]

Launch SSMS as Administrator: Open SQL Server Management Studio and connect using Windows Authentication.
![image](https://github.com/user-attachments/assets/259791b3-cd7e-4585-a454-294e962a0928)
![image](https://github.com/user-attachments/assets/58520b09-258f-457e-8244-17fc8260c437)

 
 
Go to Object Explorer tab to the left expand Databases and Right-click on databases **Student_per1** Task and select Backup.
 ![image](https://github.com/user-attachments/assets/8fa94c8d-d3b6-4b96-8916-e70c649e5aa9)
 ![image](https://github.com/user-attachments/assets/be91ff52-0152-49ea-a6fa-5e5ca2da436b)
![image](https://github.com/user-attachments/assets/e8149284-09b3-45f3-8eee-5952d026577f)

 
 
Click Add and give the backup a file name in this case will give the backup a file name of **Student_per1_11202024.bak** then click okay.
 ![image](https://github.com/user-attachments/assets/d9911c7f-a5b2-4933-afba-a76e8a5b699d)
![image](https://github.com/user-attachments/assets/3fb0c404-0e1f-4830-ac64-58c3d2abba06)

 
Next Select Media Options and under Overwrite media select **Overwrite all existing backup sets** and check **Verify backup when finished**.
![image](https://github.com/user-attachments/assets/c009cbb2-b658-4919-8144-e01ee6160327)
![image](https://github.com/user-attachments/assets/12ecac66-1387-41ef-b07b-a1bfd12486cb)
 ![image](https://github.com/user-attachments/assets/0394c6b2-3dbf-4fe7-9565-904f3b27f4e7)

 
 
Once everything has been completed click okay to perform backup and once back up is completed click okay.
 ![image](https://github.com/user-attachments/assets/098348bd-2f48-4245-9324-ff8b1244b3bb)
![image](https://github.com/user-attachments/assets/9fdc698d-bd06-461d-8a0b-989bdd0f6617)


 
**Restoring data into a new database**

Right Click on Database **Student_per2** go to Tasks, Restore, and select Database.
 ![image](https://github.com/user-attachments/assets/3647b753-a106-481c-b217-3a604938e6b6)
![image](https://github.com/user-attachments/assets/00022ecf-9eb1-4fd1-94f0-eb90278c142c)
![image](https://github.com/user-attachments/assets/4f305acd-d5b5-4556-a96e-32c33f7cc470)

 
 
Now to select a backup set select Device and select the 3-radial button to the right of device.
 ![image](https://github.com/user-attachments/assets/65577493-aa40-4caf-85c0-1302042ef898)
![image](https://github.com/user-attachments/assets/951b381a-e890-4bba-ba6f-c54f7e2ce0be)
![image](https://github.com/user-attachments/assets/d620e374-4a7d-4bb7-95a3-015932ca2409)

 
Click Add to locate the new create backup file.

 ![image](https://github.com/user-attachments/assets/574b5f2d-bdf0-4147-b384-0a30f54bc4f6)

Select the new create back up file **Student_per1_11202024.bak** from the options and click okay.
![image](https://github.com/user-attachments/assets/e26cacac-d10c-45ad-9660-00e01be1dd31)
 ![image](https://github.com/user-attachments/assets/90fab42b-80ef-48f2-98cf-d76d4d9d0768)

 
Verify the Database and the Destination information is correct as this very important. Next click the options tab.
![image](https://github.com/user-attachments/assets/9107c56a-c04f-40bb-92f5-8d2ff7d0b9e2)
 ![image](https://github.com/user-attachments/assets/f2a86094-5a42-416b-933b-cbfc1ac90895)

 
Now under Restore options select **Overwrite the existing database** and under Server connections select **Close existing connections to destination database**. Now that everything has been selected click okay to complete the database restore.

 ![image](https://github.com/user-attachments/assets/f72477f8-6132-4062-9a7b-087136e332bf)
 ![image](https://github.com/user-attachments/assets/a4cbce86-b68f-4455-9714-91424deee051)
 ![image](https://github.com/user-attachments/assets/07be033c-17e2-4eb5-9bd2-758eb71eee23)

 
 
This completes the SSMS backup and restore process.

