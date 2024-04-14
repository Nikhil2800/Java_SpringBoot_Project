
Student Management App built with Java, Spring Boot, and utilizing MySQL as the database management system and Thymeleaf as the template engine

Features :

View a list of student. 

Add new student to the database.

Update existing student information.

Delete student from the database.

Technologies Used

Java 

Spring Boot 

Thymeleaf 

MySQL 

HTML5

css3

Bootstrap 

Requirements Java Development Kit (JDK) 8 or higher. 

MySQL database server. Maven build tool.

Before running the application, make sure to set up the MySQL database with the required schema and data.

Update the database connection details in the application.properties file located in the src/main/resources directory to match your MySQL database configuration.

Run the application using Maven:

mvn spring-boot:run Open your web browser and go to the following link to access the application: http://localhost:8081/ Using the Application Now that you have successfully set up the Customer Management CRUD Application, you can start using its features to manage customer information. 


Here's what you can do:

View Customers: Access the link provided above (http://localhost:8081/) to see a list of existing customers.

Add New Customers: Click on the "Add Customer" button to navigate to the customer creation form. Fill in the required details and click "Save" to add a new customer to the database.

Update Customer Information: On the list of customers, you can click the "Update" button next to any customer's entry to open the customer update form. Modify the information as needed and click "Save" to update the customer's details.

Delete Customers: In the customer list, each entry is accompanied by a "Delete" button. Click this button to remove a customer from the database.
