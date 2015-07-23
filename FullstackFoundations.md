##Lesson 1

###ORM(Object-Relational Mapping)

ORM For python
**SQLAlchemy**

database_setup.py
	
* Configuration
* Class
* Table
* Mapper 

##### Configuration

At beginning of file

- imports all modules
- creates instance of declarative base

At end of file

creates(or connects) the database and adds tables and columns

##### Class

- representation of table as a python class
- extends the base class
- nested inside will be table and mapper code

##### Table

represents tables

syntax:

```
__tablename__ = 'some_table'
```

##### Mapper

maps python objects to columns in our DB

syntax

```
columnName = Column(attributes, ...)
```

examples attributes:

-	String
-	Integer
-	relationship(class)
-	nullable
-	primary_key
-	ForeignKey

