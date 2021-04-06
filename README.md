# dev-ent-java-microserv-spring-final-proj-template
Spring Final Project Template

This my description of my final project!
Creat the database: 

CREATE DATABASE academysara;
USE academysara;
CREATE TABLE IF NOT EXISTS academy_registration (
first_name VARCHAR(255) NOT NULL,
last_name VARCHAR(255) NOT NULL,
Address VARCHAR(255),
Email VARCHAR(50) NOT NULL, 
CourseId INT AUTO_INCREMENT PRIMARY KEY,
ClassType VARCHAR(15),
StudentId INT NOT NULL,
created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

INSERT INTO academy_registration (first_name, last_name, address, email, ClassType, StudentId) VALUES ('Sara','Safari','1799 Lancaster St.','sara.sa@gmail.com', 'Online' , '98527');

INSERT INTO academy_registration (first_name, last_name, Address, Email, ClassType, StudentId) VALUES ('Martin','Vallery','1099 Main St.','martin.va@gmail.com', 'Campus' , '90583');

INSERT INTO academy_registration (first_name, last_name, Address, Email, ClassType, StudentId) VALUES ('Maria','Hun','599 Ross St.','maria.h@gmail.com', 'Online' , '91401');


URL by :
curl http://ec2-52-13-87-137.us-west-2.compute.amazonaws.com:8080/spring-proj-template/printAllUsers


