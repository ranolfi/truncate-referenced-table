This stored procedure can help when you want to truncate a table in SQL Server but it is referenced by a foreign key constraint.

It is used as:

`truncate_referenced_table 'tablename'`.

Based on an answer by [Peter Szanto](https://stackoverflow.com/users/157591/peter-szanto) on Stack Overflow: [Cannot truncate table because it is being referenced by a FOREIGN KEY constraint?](https://stackoverflow.com/a/13249209/3258851). With additional logic to preserve disabled FK status.

See authors and license information included in the procedure code.
