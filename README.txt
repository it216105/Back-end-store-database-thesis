create table world.student(

id int not null primary key auto_increment,
firstName varchar(50),
lastName varchar(50),
sex varchar(1),
dob date,
email varchar(250) not null,
section varchar(100),
country varchar(100),
firstAttempt boolean,
subjects varchar (500),
unique (email)
);
 

insert into world.student values(2,"ioanna","tsara","F","1997-05-03","tsara.cbv@mail.com","Graduate","GREECE",1,"Site for learning java")	
insert into world.student values(3,"Nikos","Aravanis","M","2000-06-03","aravacbv@mail.com","Graduate","GREECE",1,"create site for technology")	
insert into world.student values(4,"Katerina","Stasinopoulou","F","1993-07-05","katestas@mail.com","Post Graduate","USA",1,"android app for parking")	
insert into world.student values(5,"Antonis","Mpalarinos","M","1995-01-01","balara.ant@mail.com","Post Graduate","GREECE",1,"android app for remote control")	
insert into world.student values(6,"Iliana","Nikolopoulou","F","1999-01-01","nikili@mail.com"," Graduate","GREECE",1,"create site for Computer Science")	
insert into world.student values(7,"Petros","Papadopoulos","M","1998-08-03","papadopetr@mail.com","Graduate","GREECE",1,"Learn Mathmatics")	