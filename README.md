# QueueZero

Introduction:
QueueZero is a web-based queue management system built using Java Servlets, JSP, and JDBC.It aims to replace manual token systems in public places like hospitals, banks, and offices.
Users can generate queue tokens, track their current position, and admins can efficiently manage or call the next user — all through a simple web interface.

Setup Instructions:

1.Clone the Repository
git clone https://github.com/<your-username>/QueueZero.git

2.Open Project
Open the project in NetBeans IDE.

3.Database Setup
Create a database named queuezero_db in MySQL.
Import the SQL file (if provided) or create tables manually.

4.Update Credentials
Edit DBConnection.java with your MySQL username and password:
String url = "jdbc:mysql://localhost:3306/queuezero_db";
String username = "root";
String password = "yourpassword";

5.Run on Tomcat
Right-click on the project → Run.

6.Access Application
Open your browser and visit:
http://localhost:8080/QueueZero/

Tech Stack / Software Dependencies:

1.Frontend: HTML, CSS, JavaScript

2.Backend: Java Servlets, JSP

3.Database: MySQL

4.Connectivity: JDBC

5.Server: Apache Tomcat

6.IDE: NetBeans
