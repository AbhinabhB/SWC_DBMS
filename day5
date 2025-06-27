create database db_swc;
use db_swc;

/*create table tb_employee(
	EmployeeID int identity(100, 1) primary key,
	FirstName varchar(40),
	LastName varchar(40),
	age int,
	city varchar(100),
	salary decimal(10, 2)
);*/

insert into tb_employee(firstname, lastname, age, city, salary) values
('Kalai', 'Marshall', 25, 'Chennai', 150000.00),
('Ab', 'Bob', 20, 'Mohali', 100000.00),
('Krek', 'Ken', 29, 'Kolkata', 20000.00),
('Rick', 'Rind', 34, 'Mumbai', 100000.00),
('John', 'Tor', 22, 'Delhi', 30000.00);

-- Q.1
select * from tb_employee;

-- Q.2
select firstname, salary
from tb_employee;

-- Q.3
select * 
from tb_employee
where age > 30;

-- Q.4
select * 
from tb_employee
where city = 'Delhi';

-- Q.5
select *
from tb_employee
order by salary desc;

-- Q.6
update tb_employee set salary = 55000.00 where EmployeeID = 103;
select * from tb_employee where EmployeeID = 103;

-- Q.7
delete tb_employee where EmployeeID = 104;
select * from tb_employee;

-- Q.8
insert into tb_employee values
('Nikita', 'Ramesh', 30, 'Chennai', 68000.00);
select * from tb_employee;

-- Q.9
select * 
from tb_employee
where salary > 60000;

-- Q.10
select city as City, count(*) as CountOf
from tb_employee
group by city;
