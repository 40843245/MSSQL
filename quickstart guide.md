# quickstart guide

Step 1:

check system requirements.

+ [SQL Server 2016 and 2017 system requirements](https://learn.microsoft.com/en-us/sql/sql-server/install/hardware-and-software-requirements-for-installing-sql-server?view=sql-server-ver16)

+ [SQL Server 2019 system requirements](https://learn.microsoft.com/en-us/sql/sql-server/install/hardware-and-software-requirements-for-installing-sql-server-2019?view=sql-server-ver16)

Step 2:

Install installer file

+ [Easy installer for SQL sever 2016 developer edition (web page in english)](https://www.microsoft.com/en-us/download/details.aspx?id=103438&msockid=1263be660fb767bf0324abc30ea26611)

+ [for SQL server 2022](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

Step 3:

Follow the instruction when installing SQL Server with its installer file.

For more detailed instruction, you can see MSDS [SQL Server installation guide](https://learn.microsoft.com/en-us/sql/database-engine/install-windows/install-sql-server?view=sql-server-ver16)

Take SQL Server 2016 installer as example.

1. Open SQL Server installer center by executing `..\setup.exe` file (one of installer file).
2. select `install`, then click `add new one ...` link.

<img width="615" alt="image" src="https://github.com/user-attachments/assets/e89238ca-fe39-4b0f-8414-1bf66beb069d" />

3. 

+ click free edition radio button then select kind of free edition (for example, developer edition) if you want to use free version
+ or, click product key radio button then fill in your product key if you want to use pro version (you must have product key)

Then, click `Next` button.

<img width="604" alt="image" src="https://github.com/user-attachments/assets/c59d47bd-0362-4d34-9bfa-c0ae0af9ba04" />

4. tick on `I agree ...` checkbox, then click `Next` button.

<img width="742" alt="image" src="https://github.com/user-attachments/assets/3d7fc354-6335-4678-a314-6e210d078491" />

5. select tools that you want to install and set destination directory, then click `Next` button.

![image](https://github.com/user-attachments/assets/b47d1fb2-8f97-4902-a430-63465c11b8fb)

6. click `default execution individual` radio button if you want to use default.

Then check 

+ id number of `execution individual`
+ destination directory of SQL Server
+ etc

And click `Next` button.

<img width="736" alt="1" src="https://github.com/user-attachments/assets/615deddd-f8b7-44cd-a137-5b9c6df67fea" />

7. select `mixin ...` radio button then fill in password. 

> [!WARNING]
> If don't select `mixin ...` radio button, one can not use `SA` approach to login for connection of SQL Server.

Then click `Next` button.

8. Wait for a moment.
9. Congragulations.


 
