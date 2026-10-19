
# MySQL JDBC Project

## Aim
To connect a Java application to MySQL using JDBC,
retrieve user records, and display them.

## Technologies
- Java 17+
- MySQL
- JDBC
- Maven
- MySQL Connector/J

## Database
- Database: mydatabase
- Table: users
- Columns: id, username, email

## How to Run
1. Install Java, Maven, and MySQL.
2. Execute schema.sql in MySQL Workbench.
3. Configure DB_USERNAME and DB_PASSWORD.
4. Run the project using Maven:

   mvn clean compile
   mvn exec:java -Dexec.mainClass=Main

## Expected Output
User ID: 1, Username: johndoe, Email: johndoe@example.com
User ID: 2, Username: janedoe, Email: janedoe@example.com
User ID: 3, Username: alice, Email: alice@example.com
