### SQL Commands

SQL commands are mainly categorized into four types:

1. **DDL (Data Definition Language)**:
   - DDL statements define the structure of data.
   - They create and modify database objects such as types and numbers of attributes, datatypes of columns, and various keys such as primary and foreign keys.
   - Commands:
     - `CREATE`
     - `ALTER`
     - `DROP`
     - `TRUNCATE`
     - `COMMENT`
     - `RENAME`

2. **DML (Data Manipulation Language)**:
   - DML commands are used to modify the data present in the database.
   - Commands:
     - `SELECT`
     - `INSERT`
     - `UPDATE`
     - `DELETE`
     - `MERGE`
     - `CALL`
     - `EXPLAIN PLAN`

3. **DCL (Data Control Language)**:
   - DCL commands are used to control access to data stored in a database and to implement security on database objects.
   - Commands:
     - `GRANT`
     - `REVOKE`

4. **TCL (Transaction Control Language)**:
   - TCL commands help users manage and control database transactions, which are sets of SQL statements executed on data stored in a Database Management System (DBMS).
   - Commands:
     - `COMMIT`
     - `ROLLBACK`
     - `SAVEPOINT`
     - `SET TRANSACTION`

- [DIFFERENCE BETWEEN DROP, TRUNCATE AND DELET](https://github.com/Bibek417/SQL-Proficiency/blob/main/DELET%20V%20TRUNCATE%20V%20DROP.jpg)
  - Delete is a DML language but Drop and Truncate are DDL language.
  - Delete drops the rows in the table, Truncate also drop the rows in the table but the difference between these two is delete has a rollback option but Truncate doesn't have this type of feature.
  - Drop and Truncate both are DDL languages but the difference is Drop will delete everything the whole data and the constraints associated with them.
  
