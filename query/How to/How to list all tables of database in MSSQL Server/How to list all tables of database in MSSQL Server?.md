# How to list all tables of database in MSSQL Server?
According to ScottStonehouse's answer in post [How do I get list of all tables in a database using TSQL?](https://stackoverflow.com/questions/175415/how-do-i-get-list-of-all-tables-in-a-database-using-tsql)

> [!WARNING]
> These article is only for SQL Server 2000, 2005, 2008, 2012, 2014, 2016, 2017 or 2019, 

To list all tables from all databases, make sure you don't use any database, then execute these commands.

```
SELECT * FROM INFORMATION_SCHEMA.TABLES WHERE TABLE_TYPE='BASE TABLE';
```

To list all tables from specific database, execute these commands.

```
use <databaseName>; -- execute this line to change current database as database whose name is <databaseName>, if it's current database, you can omit this statement.

SELECT * FROM INFORMATION_SCHEMA.TABLES WHERE TABLE_TYPE='BASE TABLE';
```

where 

`<databaseName>` is the database name.

## reference
[How do I get list of all tables in a database using TSQL?](https://stackoverflow.com/questions/175415/how-do-i-get-list-of-all-tables-in-a-database-using-tsql)
