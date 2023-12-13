# FashionSalesWebsite
Fashion sales website
•Technical: JSP,JSTL
•Build: Maven Project
•Apache Tomcat® 9.
•Relational database management system: **MySQL Connector Java 8.0.31**
•Hibernate core ORM functionality: [**Hibernate 5.4.33(https://mvnrepository.com/artifact/org.hibernate/hibernate-core/6.1.5.Final)
•Integration for c3p0 Connection pooling into Hibernate ORM: **Hibernate C3P0 Relocation 5.6.14.Final**
•Frontend frameworks : [Bootstrap], [jQuery], [AJAX]()
•Design pattern : MVC , DAO
•Integrated development environment (IDE) : Eclipse

How to run
1.Download and setup MySQL Community Server and MySQL Workbench.
2.Download this repository.
3.MySQL Workbench -> Server -> Data Import -> Import from Self-Contained File -> ... -> Select Database to Import -> Choose Dump Structure and Data -> Start Import.
4.Eclipse -> Open.
5.Wait for Maven download and setup dependencies.
6.Setup [Apache Tomcat]

Note
1.Change the MySQL connection in persistence.xml to your localhost.
2.Password field of user and customer is encrypted by MD5. Use this for login:
◦For user: admin@gmail.com | admin
◦For customer: customer@gmail.com | customer 

