# naming convention of key constraint in SQL Server
By default the SQL Server will use naming convention to determine the name of key constraint when it is created.

## default naming convention
### primary key

```
{defaultKeyConstraintNameForPrimaryKey} := {keyConstraintPrefixForPrimaryKey}{seperator}<tableNameWithPrimaryKey>
```

where

```
{keyConstraintPrefixForPrimaryKey} := PK

{seperator} := _
```

and 

`<tableNameWithPrimaryKey>` is the table name that has key constraint for primary key.

### foreign key

```
{defaultKeyConstraintNameForForiegnKey} := {keyConstraintPrefixForForiegnKey}{seperator}<tableNameWithPrimaryKey>{seperator}<tableNameWithForeignKey>
```

where

```
{defaultKeyConstraintNameForForiegnKey} := FK

{seperator} := _
```

and 

`<tableNameWithPrimaryKey>` is the table name that has key constraint for primary key.

`<tableNameWithForeignKey>` is the table name that has key constraint for foreign key.

### examples
See [Mastering SQL Server Database Constraints: Default Naming Conventions & Examples](https://www.adventuresinmachinelearning.com/mastering-sql-server-database-constraints-default-naming-conventions-examples/)

## reference
See [Mastering SQL Server Database Constraints: Default Naming Conventions & Examples](https://www.adventuresinmachinelearning.com/mastering-sql-server-database-constraints-default-naming-conventions-examples/)
