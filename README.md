# Database Migration Using Flyway in Spring Boot

<a href="https://javatodev.com/flyway-spring-boot/" target="blank">
    <img align="center" src="https://javatodev.com/wp-content/uploads/2020/10/Database-Migration-Using-Flyway-in-Spring-Boot-1-800x450.png" alt="Database Migration Using Flyway in Spring Boot"/></a>

<p align="left">
Flyway one of the best open-source database migration tool. Flyway supports to write migrations in SQL and Java (for advanced data transformations or dealing with LOB). Here we are discussing how we can use flyway in spring boot application and what are the best practices we could follow in such a setup.

Supported Databases For Flyway

There are more than 10 databases that support for flyway to do database migrations.

- Oracle (incl. Amazon RDS)
- MySQL (incl. Amazon RDS, Azure Database & Google Cloud SQL)
- Aurora MySQL
- MariaDB (incl. Amazon RDS)
- Percona XtraDB Cluster
- TestContainers
- SQL Server (incl. Amazon RDS & Azure SQL Database)
- Azure Synapse (Formerly Data Warehouse)
- PostgreSQL (incl. Amazon RDS, Azure Database, Google Cloud SQL & Heroku)
- Aurora PostgreSQL
- Redshift
- CockroachDB
- DB2
- SAP HANA
- Sybase ASE
- Informix
- HSQLDB
- H2
- Derby
- Snowflake
- SQLite
- Firebird

Main topics we are going to discuss here,

- Adding Required Dependencies
- Configure Database Properties
- Defining Flyway Migration Scripts
- Prefix
- Versioned Migration – V
- Undo Migration – U
- Repeatable Migrations – R
- Version
- Description
- Starting the app with migrations
- Define Gradle Task To Generate Flyway Scripts
- Stop Running Flyway Migrations

Technologies Going to Use,

- Spring Boot: 2.3.4.RELEASE
- Spring Data
- flyway-core
- Lombok
- Gradle
- Intellij Idea for IDE

</p>

📄 Original Tutorial [Database Migration Using Flyway in Spring Boot](https://javatodev.com/flyway-spring-boot/)

Related Articles 

 - [How to Create a Spring Boot Project](https://javatodev.com/how-to-create-a-spring-boot-project/)
 - [Spring Boot REST API Using JPA, Hibernate, MySQL Tutorial](https://javatodev.com/spring-boot-mysql/)
 - [Spring Boot REST API Using Spring Data MongoDB Tutorial](https://javatodev.com/spring-boot-mongodb-crud-api/)
 - [Spring Boot REST API CRUD With DynamoDB Tutorial](https://javatodev.com/spring-boot-dynamo-db-crud-tutorial/)
