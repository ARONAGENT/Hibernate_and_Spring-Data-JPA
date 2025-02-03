# Spring Boot with Hibernate & Spring Data JPA

## Project Description
This project focuses on integrating Hibernate and Spring Data JPA into a Spring Boot application. It covers setting up a relational database, working with ORM, JPA repositories, and performing CRUD operations in a cloud database. It also explores various JPA mappings and query methods, utilizing the official Spring Data JPA documentation for reference.

## Topics Covered

### 1. Configure MySQL Database On Aiven Cloud.
- Setting up MySQL as a cloud database in aiven cloud 
- For Database Management use MySQL shell to connect your cloud Database 

### 2. Hibernate ORM, JPA, Entities, and Tables in Spring Data JPA
- Introduction to Hibernate ORM and JPA
- Defining entities and creating database tables using JPA annotations

### 3. Spring Data JPA Interfaces and Dynamic Query Methods
- Understanding Spring Data JPA repositories
- Implementing dynamic query methods
- **Reference PDF included:** All JPA methods from [Spring Data JPA documentation](https://docs.spring.io/spring-data/jpa/reference/repositories/query-keywords-reference.html)
- **Executions** - [0000.springDataJpaMethods.pdf](https://github.com/user-attachments/files/18646912/0000.springDataJpaMethods.pdf)

### 4. Sorting and Pagination in Spring Data JPA
- Implementing sorting and pagination in JPA queries
- Using Pageable and Sort classes in Spring Data JPA

### 5. Spring Data JPA Mappings Part 1 - One-To-One Mapping
- Defining one-to-one relationships in JPA
- Implementing @OneToOne annotation
- **Image included:** One-to-one mapping results
- **One to One Mapping (if one manger is assign to another department then)**
 ![00 one to one (if one manger is assign to another department then)](https://github.com/user-attachments/assets/c7521b29-fc82-41f6-bac8-59368fa27f2d)


### 6. Spring Data JPA Mappings Part 2 - One-To-Many, Many-To-Many Mapping
- Implementing @OneToMany and @ManyToMany relationships
- Best practices for handling JPA associations
- **Images included:** One-to-many and many-to-many mapping results
-**One to Many [Bidirectional](one department have many employees)**
 
 ![01 one to many (one department have many employees)](https://github.com/user-attachments/assets/092b22de-45fb-4b5e-b32a-5827dc6c599f)

 -**Many to Many Mapping  (many freelancer assign to many department)**
 
 ![02 (many  to many)  many freelancer assign to many department](https://github.com/user-attachments/assets/58591845-24d0-4727-a53e-34ea5d018873)


## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/ARONAGENT/Hibernate_and_Spring-Data-JPA.git
   cd spring-boot-jpa
   ```
2. Configure database properties in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://your-cloud-db-url:3306/your-database
   spring.datasource.username=your-username
   spring.datasource.password=your-password
   spring.jpa.hibernate.ddl-auto=update
   ```
3. Build the project using Maven:
   ```bash
   mvn clean install
   ```
4. Run the application:
   ```bash
   mvn spring-boot:run
   ```
5. Access the MySQL database via DBeaver or MySQL Workbench.

## Prerequisites
- Java 21
- Maven
- IntelliJ IDEA
- MySQL Cloud Database

## Contributing
Feel free to fork this repository and contribute with pull requests to improve the project.

## License
This project is open-source and available under the MIT License.

