

## Description

This project is a basic CRUD (Create, Read, Update, Delete) system developed using Java and Spring Boot for the backend and React for the frontend. The system allows the creation, reading, updating, and deletion of data through a web interface.

## Technologies

- **Backend:**
  - Java
  - Spring Boot
  - Spring Data JPA
  - MySQL
  - Maven

- **Frontend:**
  - React
  - Axios (for API requests)
  - CSS/Bootstrap (for styling)

## Installation

### Backend

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name/backend
    ```

2. Ensure you have Maven and Java installed.



4. Configure the `application.properties` file located in `src/main/resources/` with your MySQL credentials:

    ```
    server.port=8082
    spring.jpa.hibernate.ddl-auto=update
    spring.datasource.url = jdbc:mysql://localhost:3306/database_name
    spring.datasource.username=yourUsername

    spring.datasource.password=yourPassword
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    ```

5. Run the application:

    ```bash
    mvn spring-boot:run
    ```

6. The backend server should now be running on `http://localhost:8082`.

### Frontend

1. Open a new terminal and navigate to the `frontend` directory:

    ```bash
    cd ../frontend
    ```

2. Ensure you have Node.js and npm installed. Then, install the dependencies and start the application:

    ```bash
    npm install
    npm start
    ```

3. The frontend application should now be running on `http://localhost:3000`.

## Usage

- Open your browser and navigate to `http://localhost:3000`.
- Use the web interface to perform CRUD operations.
  - **Create:** Add new records.
  - **Read:** View records.
  - **Update:** Modify existing records.
  - **Delete:** Remove records.



