#  Expenses Tracker WebApp

##  Overview  
Leading a team on an **Expense Tracker WebApp** (Spring Boot, MySQL, Docker), I built the **frontend features** and guided containerized deployment for scalability, strengthening my **leadership and collaboration skills**.  

The app provides secure authentication, CRUD operations for expenses, filtering, and a user-friendly interface powered by **Thymeleaf & Bootstrap**. UI/UX designs were created using **Adobe XD** for an intuitive user experience.  

---

##  Team Roles  

### Team Leader & Frontend Developer – Hafiza Tahreem Arshad
- Coordinated project tasks and team communication  
- Designed UI/UX mockups and prototypes using **Adobe XD**  
- Developed frontend using **Thymeleaf + Bootstrap**  
- Integrated frontend with backend APIs for seamless expense management  

### Backend Developer – Muhammad Hammad
- Built REST APIs with Spring Boot  
- Handled CRUD operations and business logic  
- Implemented filtering feature  

### Security Engineer –  Shayan Ali
- Integrated Spring Security for authentication/authorization  
- Implemented password encryption & secure session handling  

### Database Engineer – Maheen Zahra
- Designed MySQL schema for expense tracking  
- Managed queries and optimized database performance  

###  DevOps Engineer – Mahnoor Fatima
- Set up Docker for containerized deployment  
- Configured application properties for production  
- Managed build pipelines  

---

## Technologies Used  
- **Java**, **Spring Boot**, **Spring Security**, **Spring Data JPA**  
- **MySQL**  
- **Thymeleaf**, **Bootstrap**  
- **Adobe XD** (UI/UX design)  
- **Docker**  

---

## Features  
- User Authentication & Authorization  
- CRUD Operations for Expenses  
- Filtering by categories/date ranges  
- Dockerized Deployment for scalability  
- UI/UX prototyping with Adobe XD  

---

## Getting Started  

### Clone the Repository  
```bash
git clone https://github.com/your-username/expenses-tracker.git
cd expenses-tracker
```
### Configure Database
- Create a MySQL database:
```bash
CREATE DATABASE expenses_tracker;
```
- Update src/main/resources/application.properties with your MySQL username & password.

### Build the Project
```bash
mvn clean install
```
### Run the Application
```bash
java -jar target/expenses-tracker.jar
```
### Access the App
- Open your browser at: http://localhost:8080
