# Learning SQLite
### Creating a new table for Doctors

```SQL
CREATE TABLE Doctors (
  DoctorID INTEGER PRIMARY KEY AUTOINCREMENT,
  Name TEXT NOT NULL,
  Surname Text NOT NULL,
  Multiplier DECIMAL NOT NULL
);
```
### Inserting some data into my new table

```SQL
INSERT INTO Doctors (Name, Surname, Multiplier)
VALUES 
( 'Anna', 'Apse', 2),
('Oskars', 'Liepiņš', 0.5),
('Jenifere', 'Pottere', 3.2);
```
  ### Deleting rows (records) froom the table
  ``` SQL
DELETE FROM Doctors WHRERE DoctorID > 10;
