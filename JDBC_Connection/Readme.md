# JDBC

## About JDBC
JDBC (Java Database Connectivity) is an API in Java that allows applications to interact with databases. It provides a standard way to connect, execute queries, and retrieve results from relational databases like MySQL, Oracle, and PostgreSQL.

### Key Features
- Establishes connection between Java applications and databases  
- Executes SQL queries (SELECT, INSERT, UPDATE, DELETE)  
- Retrieves and processes results  
- Supports multiple database drivers through a common interface  

### Main Components
- **DriverManager** – Manages database drivers and connections  
- **Connection** – Represents a session with a database  
- **Statement / PreparedStatement / CallableStatement** – Used to execute SQL queries  
- **ResultSet** – Stores the result of executed queries  

### Steps to Use JDBC
1. Load and register the driver  
2. Establish a connection  
3. Create a statement  
4. Execute SQL queries  
5. Process the results  
6. Close the connection  

## Terminal Code
```
javac -cp ".;lib/mysql-connector-j-9.5.0.jar" Main.java
java -cp ".;lib/mysql-connector-j-9.5.0.jar" Main
```