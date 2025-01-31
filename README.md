	NAME:MUGWANEZA Oscar chance
	REG:2401001423
	LEACTURER NAME: Dr BUGINGO Emmanuel
	Individual assignment of Database management system
	School university of Kigali Musanze campus



1. Title of the Project:
Road Management System (RMS)
________________________________________
2. Description of the Project:
The Road Management System is an integrated solution designed to manage road networks, ensuring efficient road maintenance, traffic flow management, incident reporting, and public engagement. The system provides a platform for road authorities, maintenance teams, and the public to monitor and improve road conditions.
road table
Entity of road
Attribute	Data types	Description
roadID	a.Integer
	Unique identifier for each report
Road Name	b.varchar	 Name of the road
Lengths	c. a.Integer
	Length of the road in kilometers

Table of posture/traffic


Attribute	
Data Type
	
Description

Reportid	
integer	Unique identifier for each report


RoadID	integer	Foreign key references road id

Traffic acount	integer	Number of vehicles counted in the road
date	date	Date of traffic report
Peak times	Varchar(50)	Peak time when traffic was highest









Table of user/police

Attribute
	Data type
	Description

PoliceID 
	
Integer	Unique identifier for each police primary key

Police name
	
string	
Name of police
email
	string	
Police email address

Role
	
string	
Police role
phone
	string	Phone number of police










PHYSICAL RELTIONAL MODEL
PHYSICAL RELATIONALMODEL FOR ROADS ENTITY













PHYSICAL RELATIONALMODEL FOR TRAFFIC ENTITY






 



PHYSICAL RELATIONALMODEL FOR TRAFFIC ENTITY














Logical data model
Road  (Roadid,road_name,Lengths)
Police (POLICEid,POLICE_NAME,EMAIL,Role,phone)
Traffic (reportedid ,roadid#, Policeid# ,Traffic_account ,date)



ENTITY RELATIONSHIP DIAGRAM

     












