ABSTRACT

The Hospital Management System (HMS) proposed here offers an integrated solution for optimizing the operations of a medical facility. This system consists of two primary modules: Admin and Doctor. The zadmin module enables administrators to securely log in and access a centralized dashboard displaying key metrics like total patients and appointments. Admins can efficiently manage doctor profiles, patient records, and appointments, facilitating tasks such as scheduling, rescheduling, and cancellations. Additionally, the system provides reporting capabilities to generate insights into patient statistics, appointments, and revenue. On the other hand, the Doctor module allows medical practitioners to access their schedules, view patient histories, manage appointments, prescribe medications, and generate digital prescriptions. The system leverages modern web technologies such as HTML, CSS, JavaScript, PHP, and MySQL to deliver a user-friendly interface, robust backend functionality, and efficient data management. With role-based access control and tailored functionalities, this HMS aims to enhance operational efficiency, streamline workflow processes, and improve overall patient care within the medical facility.

FEATURES

Admin Module:

1.	Login: Admins can log in to the system securely using their credentials.
2.	Dashboard: Upon logging in, the admin is presented with a dashboard displaying key metrics such as total patients, appointments, etc.
3.	Manage Doctors: Admins can add, edit, or delete doctor profiles, including their specialization and contact information.
4.	Manage Patients: Admins can add, edit, or delete patient records, including personal details and medical history.
5.	Appointments: Admins can schedule, reschedule, or cancel appointments between doctors and patients.
6.	Reports: Generate reports on various aspects such as patient statistics, appointments, revenue, etc.
   
Doctor Module:

1.	Login: Doctors can log in to the system using their credentials.
2.	Dashboard: Doctors are presented with a dashboard showing their schedule, upcoming appointments, and patient history.
3.	Manage Appointments: Doctors can view their appointments, mark them as attended, reschedule, or cancel if necessary.
4.	Patient Records: Access and update patient records, including medical history, diagnosis, and prescribed medications.
5.	Prescriptions: Doctors can prescribe medications, specify dosage, and generate digital prescriptions for patients.
6.	Reports: Access reports related to patient history, appointments.
   
TECHNOLOGIES USED

•	Backend: PHP
•	Frontend: HTML, CSS, JavaScript
•	Database: MySQL
•	Authentication: PHP sessions
•	Deployment: Apache Server

PREREQUISITES

•	PHP 7.x
•	MySQL
•	Apache Server
•	Web Browser


Steps

1.	Import Database
•	Create a MySQL database and import the hmisphp.sql file provided in the project.

3.	Start Apache Server
•	Make sure Apache Server is running.

5.	Access the Application
               http://localhost/Hospital-PHP

Installation steps in AZURE:

1. Clone the HMS Repository
Clone the HMS repository to your local machine using Git:
git clone https://github.com/sanjaySJJ/hms.git

2.Navigate to Project Directory:
Change into the project directory:
cd repository

3.Create Virtual Environment:
Set up a virtual environment for the project to manage dependencies:
$ sudo dnf update
$ sudo dnf install https://rpms.remirepo.net/enterprise/remi-release-9.rpm
$ sudo dnf module list php
$ sudo dnf module enable php:remi-<VERSION>
$ sudo dnf install php 
$ php -v 
Activate the virtual environment:
On macOS/Linux:
source venv/bin/activate
On Windows:
venv\Scripts\activate

4.Configure Azure Database
Create a MySQL Database
Log in to the Azure Portal.
Navigate to "Azure Database for MySQL" and create a new MySQL database.
Note down the connection details (server name, username, password, etc.).
Import Database Schema
Export the hmisphp.sql file from the CRMS project.
Import this file into your Azure MySQL database using Azure Database for MySQL Tools or Azure Data Studio.

USAGE:

1.	Admin Module:
•	Handles user authentication and access control for administrators.
•	Facilitates management tasks such as doctor profiles, patient records, and appointment scheduling.
•	Provides reporting capabilities to analyze key metrics and optimize hospital operations.

3.	Doctor Module:
•	Allows doctors to log in securely and manage their schedules and appointments.
•	Provides access to patient records for consultations, diagnoses, and prescription management.
•	Offers reporting functionalities to monitor patient progress and treatment outcomes.

CONTRIBUTIONS:

THABRESH U
Role:Front end
Responsibilities:Create and maintain project front end(PHP,CSS,JAVASCRIPT,BOOTSTRAP)

ROGITH R
Role:Back end
Responsibilities:create and maintain project back end(PHP and MYSQL)

SANJAY B
Role:Deploy project
Responsibilities:To deploy a Hospital management system project in azure cloud

PRANESH N
Role:Voice Over 
Responsibilities:Give step by step voice to guide the project


Azure Services used 
AZURE SERVICES USED:
 

 



 



 

 


 


PROJECT LAYOUTS:
 

 


ADMIN MODULE :

 


 


 


 

 




 

 

DOCTOR MODULE:

 
 

 



 
















