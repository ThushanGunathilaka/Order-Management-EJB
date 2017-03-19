DIT: IT13011130
NAME: Gunathilaka D. D. T. M.
EMAIL: it13011130@my.sliit.lk
DATE:14/08/2016

Assignment.pdf contains use case diagram and screen captures.
Class Diagram.vsdk contain class diagram, or in class diagram.jpg
When removing customers, pending orders are checked.

Requirements:
* JDK v1.7.0_99
* JavaEE 6
* GlassFish Server v3.1.2 or later.
* Java-DB jdbc:derby
* NetBeans IDE v7.4 or later

Instructions:
* Resolve Reference problems
* Set JavaDb path for sample data:
* -Services Window --> Databases --> Java DB --> Properties
* -Database Location : <Project_Dir>\javadb\
* -Or use <Project_Dir>\javadb\OrderManagement Query.sql
* -Or use,
* --Database:sample | Username:N/A | Password:N/A | Schema:APP | URL: jdbc:derby://localhost:1527/sample
* -- You`ll well get a warning popup if you try to create orders without customers.
* Clean Build for the first time run.

Defaults:
http://localhost:8080/OrderManagement-war/HomePage
jdbc:derby://localhost:1527/sample [ on APP]