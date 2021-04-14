## Data Definiton Language

#### Datatypes
* Numeric
    * INT : Whole numbers
    * FLOAT(M,D) : Decimal numbers (approximate)
    * DECIMAL (M,D) : Decimal numbers (precise) 

* NON-Numeric
    * CHAR(N) : Fixed length character
    * VARCHAR(N) : Varing length character
    * ENUM('M','F') : Value from a defined list
    * BOOLEAN : True or False

* Date
    * DATE : Date (YYYY-MM-DD)
    * DATETIME : Date and Time (YYYY-MM-DD HH-MM-SS)
    * TIME : Time (HHH-MM-SS)
    * YEAR : Year (YYYY)

### Primary Key
1. A primary key must be unique
2. A primary key cannot be NULL
3. A table can only have on primary key

### Foreign Key
1. A foregin key is used to link two tables toghether.
2. A foregin key is a column whose values match the value of another tables primary key column.
3. A table can have mulitple foreign keys.
4. Primary Key -> Parent Table
   Foregin Key -> Child Table