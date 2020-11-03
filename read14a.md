# Database Normalization
## Database Normalization is a process used to organize a database into tables and columns.

#### limiting a table to one purpose you reduce the number of duplicate data contained within your database.

### Reasons for Database Normalization :

* to minimize duplicate data
* to minimize or avoid data modification issues
* to simplify queries

#### Data Duplication and Modification Anomalies,Duplicated information presents two problems:

* It increases storage and decrease performance.
* It becomes more difficult to maintain data changes.

#### Insert Anomaly :  in order to create the record, we need provide a primary key.  In our case this is the EmployeeID.
#### Update Anomaly : there are multiple updates that need to be made.  If we don’t update all rows, then inconsistencies appear.

1. First Normal Form : The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
2. Second Normal Form : The table is in first normal form and all the columns depend on the table’s primary key.
3. Third Normal Form :  the table is in second normal form and all of its columns are not transitively dependent on the primary key.
