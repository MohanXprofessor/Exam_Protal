# Exam_Protal
Java +Angular+MySQL
# Exam Portal 📝

An online exam management system built using **Java**, **Spring Boot**, **Hibernate**, and **Angular**. This application allows students to take exams, view results, and track their progress while enabling administrators to manage exam questions, schedules, and users.

## Features 🚀
- User and Admin roles with secured authentication.
- Online exam creation and management with auto-grading.
- Results tracking for both students and administrators.

## Prerequisites 📋
Before running the project, ensure you have the following installed:
- Java JDK 11+
- Node.js 14+ and npm
- Angular CLI
- MySQL Database
- Maven (for managing Spring Boot dependencies)

## Installation Instructions 🛠️
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/exam-portal.git
    ```

2. Navigate to the backend Spring Boot project and install dependencies:
    ```bash
    cd exam-portal-backend
    mvn clean install
    ```

3. Update MySQL database configuration in `application.properties`:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/examportal
    spring.datasource.username=root
    spring.datasource.password=yourpassword
    ```

4. Run the Spring Boot backend:
    ```bash
    mvn spring-boot:run
    ```

5. Navigate to the Angular frontend project and install dependencies:
    ```bash
    cd exam-portal-frontend
    npm install
    ```

6. Run the Angular development server:
    ```bash
    ng serve
    ```

## Tech Stack 🛠️
- **Frontend**: Angular, TypeScript, Bootstrap
- **Backend**: Spring Boot, Hibernate, MySQL
- **Tools**: Maven, Node.js, npm

## Contribution 🤝
Feel free to submit issues or pull requests if you'd like to contribute to this project!


---

Made with ❤️ by MohanXprofessor
