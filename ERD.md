# Entity and Attribute in Databases

## What is an Entity and Attribute?

- Attributes describe the characteristics or properties of an entity in a database table.  
- An entity in a database table is defined with a fixed set of attributes.

## Entity Constraints

- Constraints are rules used to restrict the values that can be stored in the columns of a database.
   
### Types of constraints include:

1. **Unique Constraint**:
   - This constraint is used for columns that need unique values.  
   - For example, 'employee IDs' should be unique in an employee table.

2. **NULL Constraint**:
   - This constraint is used to determine the columns that can have null values.  
   - For example, an employee may not need to specify their location, so the location column can have null values in an employee table.  
   - Note that the unique constraint can coexist with null constraints in a relational data model.

3. **Primary Key Constraint**:
   - Determines the columns that uniquely identify a table.  
   - A primary key constraint always enforces both the unique and not-null constraints.

4. **Referential Constraint**:
   - These are used to restrict the values taken by a column in one table based on the values that exist in another table.  
   It is a rule between two tables.  
   - According to this rule, the value that appears as a foreign key in a table is valid only if it also appears as a primary key in the table to which it refers.  
   - A given table has one primary key, but it can have multiple foreign keys.  
   - Before you assign a column as a foreign key, ensure that the primary key column of the table it refers to is present and doesn't have null or duplicate values.

5. **Semantic Constraints**: 
   - Semantic constraints impose restrictions on the values in a column.  
   - For example, all mobile numbers in India start with +91, followed by 10 digits.  
   - Using a semantic constraint for this requirement ensures that we don't get incorrect data for any row.  
   - For example, a row with a phone number +91123456789 would not be allowed to enter the database as it has only 9 digits after the country code.


