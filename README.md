![Language](https://img.shields.io/badge/language-Java%20-blue.svg)
![Technologies](https://img.shields.io/badge/technologies-Spring_boot%20-green.svg)
![Technologies](https://img.shields.io/badge/technologies-Spring_MVC%20-green.svg)
![Technologies](https://img.shields.io/badge/technologies-Spring_Security%20-green.svg)
![Technologies](https://img.shields.io/badge/technologies-Spring_Data_jpa%20-green.svg)
![Technologies](https://img.shields.io/badge/technologies-Thymeleaf_&_Bootstrap%20-purple.svg)

# Expenses-Tracker-WebApp
## Overview
The Expenses Tracker App is a robust financial management solution developed using cutting-edge technologies such as Spring Boot, Spring Security, and MySQL. With user authentication and authorization features, users can securely sign up, sign in, and perform CRUD operations on their expenses. The app's intuitive interface, powered by Thymeleaf and Bootstrap, ensures a seamless user experience. The filtering functionality allows users to efficiently organize and analyze their financial data. Explore the power of streamlined expense tracking and financial control with this feature-rich application.<br> (Screenshots below for more illustration)

## Technologies Used
- Java
- Spring boot
- Spring MVC
- Spring Security
- Spring Data (JPA)
- MySQL
- Thymeleaf
- Bootstrap

## Features
- **User Authentication and Authorization:** Securely sign up, sign in, and access the app with built-in authentication and authorization.
- **CRUD Operations:** Perform essential financial tracking actions such as adding, reading, updating, and deleting expenses.
- **Filtering:** Utilize the filtering feature to efficiently sort and view expenses based on various criteria.

---

## Docker & Containerization
This project is fully containerized using **Docker** and **Docker Compose**, ensuring consistent execution across environments.

### Dockerized Services
- **Spring Boot Application**
- **MySQL Database**
- Custom Docker network for inter-service communication

> No local installation of Java, Maven, or MySQL is required when using Docker.

---

## Getting Started

You can run this application in **two ways**:

---

### 🚀 Option 1: Run using Docker (Recommended)

#### Prerequisites
- Docker
- Docker Compose

#### Steps

1. Clone the repository:
```bash
git clone https://github.com/your-username/Expenses-Tracker-WebApp.git
cd Expenses-Tracker-WebApp
```
2. Build and start the containers:
```bash
docker compose up --build
```
3. Access the application:
```bash
http://localhost:8080
```

✅ This will automatically start:

Spring Boot application
MySQL database
Required Docker network

### 🛠 Option 2: Run Without Docker (Manual Setup)

### Prerequisites
Java 17+
Maven
MySQL

### Steps

1. **Configure Database:**
Set up MySQL database and update the application.properties file with your database configuration.

2. **Build and Run:**
Build the project using your preferred IDE or with Maven:
`mvn clean install`.

3. **Run the application:**
`java -jar target/expenses-tracker.jar`.

4. **Access the App:**
Open your web browser and navigate to `http://localhost:8080`.

## Notes
- MySQL data is stored in a Docker volume and is excluded from version control.
- Environment variables and secrets are not committed for security reasons.

---

## ScreenShots
![Example Image](screenshots/1.png) <br>
![Example Image](screenshots/2-2.png) <br>
![Example Image](screenshots/3-3.png) <br>
![Example Image](screenshots/4-4.png) <br>
![Example Image](screenshots/5-5.png) <br>
![Example Image](screenshots/6-6.png) <br>
![Example Image](screenshots/7.png) <br>
![Example Image](screenshots/8.png) <br>

## Contributions
Contributions are welcome! If you find a bug or have suggestions for improvement, feel free to open an issue or create a pull request.

## License
This project is licensed under the MIT License.
