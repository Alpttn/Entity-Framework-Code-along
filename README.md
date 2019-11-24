# Entity-Framework-Code-along
Bare template of web application using Entity Framework without Identity Framework

Run script below in query to seed database:

```
INSERT INTO Departments (Name, Budget) VALUES ('HR', 300000);
INSERT INTO Departments (Name, Budget) VALUES ('Executive Team', 2000000);
INSERT INTO Departments (Name, Budget) VALUES ('Marketing', 540000);
INSERT INTO Departments (Name, Budget) VALUES ('Occult Studies', 81200);
INSERT INTO Departments (Name, Budget) VALUES ('Silly Walks', 3800000);
INSERT INTO Departments (Name, Budget) VALUES ('IT', 45);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Allison', 'Patton', 1, 1);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Bennett', 'Foster', 2, 1);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Bobby', 'Brady', 3, 1);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Brantley', 'Jones', 4, 1);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Brian', 'Wilson', 5, 1);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Carl', 'Barringer', 6, 1);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Curtis', 'Crutchfield', 1, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Ellie', 'Ash', 2, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Eric', 'Taylor', 3, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Haroon', 'Iqbal', 4, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Jacquelyn', 'McCray', 5, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Joe', 'Snyder', 6, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Kelly', 'Coles', 1, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Kevin', 'Sadler', 2, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Maggie', 'Johnson', 3, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Matthew', 'Ross', 4, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Michael', 'Stiles', 5, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Michelle', 'Jimenez', 6, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Noah', 'Bartfield', 1, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Sarah', 'Fleming', 2, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('William', 'Wilkinson', 3, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Ali', 'Abdulle', 4, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Samuel', 'Alpren', 5, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Sam', 'Britt', 6, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Jameka', 'Echols', 1, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Josh', 'Hibray', 2, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Brian', 'Jobe', 3, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('William', 'Mathison', 4, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Clifton', 'Matuszeski', 5, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('William', 'Mitchell', 6, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Joel', 'Mondesir', 1, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Christopher', 'Morgan', 2, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Meagan', 'Mueller', 3, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Jonathan', 'Schaffer', 4, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Stephen', 'Senft', 5, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Alexander', 'Thacker', 6, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Anne', 'Vick', 1, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Rose', 'Wisotzky', 2, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Michael', 'Yankura', 3, 0);
INSERT INTO Employees (FirstName, LastName, DepartmentId, IsSupervisor) VALUES ('Selamawit', 'GebreKidan', 4, 0);
```
