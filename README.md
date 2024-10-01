RUN THIS SQL COMMANDS

CREATE DATABASE hotelMS;

use hotelMS;

create table login(username VARCHAR(50), password VARCHAR(50));

create table login2(user_name VARCHAR(50), password VARCHAR(50));

drop table login2;

SELECT * from login;

insert into login2 values ('user', '123456789');

create table room(roomnumber VARCHAR(20), availability VARCHAR(20), cleaning_status VARCHAR(20), price VARCHAR(20), bed_type VARCHAR(20));

SELECT * from employee;

create table driver(name VARCHAR(20), age VARCHAR(20), gender VARCHAR(20), company VARCHAR(20), carname VARCHAR(20), available VARCHAR(20), location VARCHAR(20));

create table employee(name VARCHAR(20), age VARCHAR(20), gender VARCHAR(20), job VARCHAR(20), salary VARCHAR(20), phone VARCHAR(20), email VARCHAR(20), aadhar VARCHAR(20));

create table department(department VARCHAR(20), budget VARCHAR(20));

INSERT into department values('office','50000');
INSERT into department values('HouseKeeping','40000');
INSERT into department values('Food','80000');
INSERT into department values('Kitchen','20000');
INSERT into department values('Security','60000');

SELECT * from department;
SELECT * from customer;

CREATE table customer(document VARCHAR(30), number VARCHAR(30), name VARCHAR(30), gender VARCHAR(30), country VARCHAR(30), room VARCHAR(30), checkintime VARCHAR(80), deposit VARCHAR(30));
