# Java-GUI---Servlet-Http-Session---JDBC

Part I:  
1. Setting up the Apache Tomcat Server  Download and set up a TOMCAT web server (or any other web server that supports the Servlet) for testing the Servlet. Please don’t  install the server on CS99.  (You may use different port other than 8080 if the port is been used, see the lecture notes for details.)  
2. Deploy and test the Servlet  Deploy and test the Hello Servlet example from the lecture note. 
--------------------------------------------------------------------------------------------  

Part II:  
1. Develop the Servlets  Design and develop Java Servlet programs to process the requests from the Book HTML GUI client using as NetBeans/Eclipse Java IDE tool.  (Please use the same Servlet names as specified below. You should also reuse the Java JDBC code developed from the previous assignment.)  
    1. Develop a dbConnection Servlet to connect to the Book database.  Use an Http session to store the database login, password, and database connection.  
    2. Develop a dbQuery Servlet to process the data query request from the client.  The Servlet should use the same database connection object stored in the Http session.  
    3. Develop a dbUpdateServlet Servlet to process the data update request from the client.  The Servlet should use the same database connection object stored in the Http session.  The Servlet should use the JDBC class from the assignment 1 to handle the JDBC and SQL details. 
    
2. Deploy and Test the Three-Tier Client-Server-Database System  Combine the above into a three-tier client/application server/database application.  You can use the simple HTML GUI to interact with the servlets. - Test the GUI with the Servlet in TOMCAT web server and your Book database.  

3. (Extra credit): Use JSF (JavaServer Face) for the Book Application - See Address Book JSF application on Chapter 30 for example.  

4. (Extra credit) Make one of the above Servlet as a web service.
