# Workshop - Demo-Dao-JDBC

This project was developed as a workshop during the *"Java COMPLETO 2023 Programação Orientada a Objetos + Projetos"* course by Professor Nelio Alves, available on [Udemy](https://www.udemy.com/course/java-curso-completo/).

It was also created as a way to test the functionality of JDBC and set up a basic MySQL database with mock data and CRUD operations. This database consists of two tables: one for vendors and another for departments, simulating the kind of database that a company might use in a simplified real-world scenario.

# Setting it up

Before you begin, ensure that you have the requirements already installed on your computer.

First, in the project files, you will find a file named `database.sql` containing the commands to generate the tables and mock data that will be used. Additionally, there is a file named `properties.db`, responsible for enabling Java to access your database.

Open MySQLWorkbench and create a new connection. Follow the details provided in the properties file mentioned above and complete the setup. If you prefer not to create a new connection, make sure to adjust the data in the properties file to match your existing connection. Be mindful that it is case-sensitive, so take your time when configuring it.

With the connection established and the properties matching, you can create a new database. If you want to use the properties file as a reference, execute the following query: `CREATE DATABASE coursejdbc` and run it. This will create a new database named 'coursejdbc', which we will be using. Open the database by double-clicking it and then run a new query using the commands found inside the `database.sql` file to set up the tables and mock data.

If you have followed the steps above, your IDE should now be properly configured and ready to run the program and access your database.

# Requirements

To run this project, it's necessary to have Java 17 (LTS) installed on your machine. The Java version I used was Java Azul Zulu 17.0.7 (LTS) ([link](https://www.azul.com/downloads/?version=java-17-lts&package=jdk#zulu)), but it should not be necessary to have this exact version for the project to work.

Furthermore, as these are source files (*src*), you also need an IDE capable of interpreting the code, with **ECLIPSE IDE** ([link](https://www.eclipse.org/downloads/)) being my choice.

As we have to work with databases, you'll need to have **MySQL** and **MySQLWorkbench** installed and running on your computer.

##

Created by @AlysonCantalice.
