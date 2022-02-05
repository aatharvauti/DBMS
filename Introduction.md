
# Database Management System
---

#### Software to Install:
- MySQL Server 8.0.28
- MySQL Workbench 8.0.28
- MySQL Shell 8.0.28

<br>

### Experiment 1: ER Diagram

Entity Relationship Diagram:

![[ER.png]]

<br>

### Experiment 2:

	CREATE DATABASE collegedb;
	
	SHOW DATABASES;
	
	USE collegedb;
	
	CREATE TABLE SE15 (
		RollNo int,
		Name varchar(25),
		Address varchar(100)
	);
	
	ALTER TABLE SE15 
	ADD (Phone int);
	
	ALTER TABLE SE15
	DROP COLUMN Phone;
	
	DESC SE15;
	
	INSERT INTO SE15 VALUES(1,'Atharva Auti','Navi Mumbai');
	
	ALTER TABLE SE15
	RENAME TO Divison15
	
	CREATE TABLE Divison15Clone
	SELECT * FROM Divison15;
	
	
	