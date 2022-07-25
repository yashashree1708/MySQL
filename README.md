USE master;
GO
CREATE DATABASE Employees ON(
NAME Employees dat,-
FILENAME='<VALID PATH>Employeesdat.mdf¹,
SIZE=10,
MAXSIZE 50,
FILEGROWTH=5)
         =
LOG ON(NAME Employees_log,
FILENAME
30
              <VALID PATH>Employeeslog.ldf',
SIZE SMB,
MAXSIZE=25MB,
FILEGROWTH=5MB);
