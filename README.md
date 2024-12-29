# iPlant - Medicinal Plants Project

## Overview
This repository contains the source code for the iPlant project, a platform dedicated to medicinal plants. The application provides features such as login, plant details, and user authentication.

The repository is organized into two main folders:
- **frontend**: Contains the front-end code for the application.
- **backend**: Contains the back-end code implemented using Java Spring Boot.

---

## Instructions to Launch the Application

### 1. Frontend
#### Prerequisites
- Node.js and npm installed.

#### Steps
1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```
   The application will be available at `http://localhost:3000`.

#### Additional Features
- **Cypress Tests**:
  To run end-to-end tests using Cypress:
  ```bash
  npx cypress open
  ```
- **Selenium Tests**:
  Ensure Selenium WebDriver is set up and run the tests in the designated folder.
- **Workflows**:
  - SonarQube analysis for code quality.
  - Selenium tests.
  - Deployment to Amazon S3.

### 2. Backend
#### Prerequisites
- Java 17 or higher installed.
- Maven installed.

#### Steps
1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Build the project:
   ```bash
   mvn clean install
   ```
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```
   The backend API will be available at `http://localhost:8080`.

#### Additional Features
- **JUnit Tests**:
  To execute unit tests:
  ```bash
  mvn test
  ```
- **Workflows**:
  - SonarQube analysis for code quality.
  - Automated execution of JUnit tests.

---

## Project Features
- **Authentication**:
  Secure login and user authentication.
- **Plant Details**:
  View and manage details of medicinal plants.
- **CI/CD**:
  Integrated workflows for testing, code analysis, and deployment.

---


