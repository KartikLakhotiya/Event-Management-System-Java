# Event Management System

This Event Management System is a web application built using Spring Boot, Maven, and MySQL. The system provides a platform for users to book events and for admins to manage and approve these bookings.

## Features

### User Features
- **Event Browsing**: Users can browse available events.
- **Event Booking**: Users can book events.
- **Booking Management**: Users can view their booking history and status.

### Admin Features
- **Event Approval**: Admins can approve or reject event bookings.
- **Event Management**: Admins can add, update, or delete events.
- **User Management**: Admins can view and manage registered users.

## Technologies Used

- **Backend**: Spring Boot
- **Build Tool**: Maven
- **Database**: MySQL
- **Frontend**: (Specify if you have used any frontend technologies like Thymeleaf, Angular, etc.)
- **Other Tools**: (e.g., Lombok, Spring Data JPA, etc.)

## Installation

### Prerequisites
- Java 11 or higher
- Maven 3.6+
- MySQL 8.0+
- (Any other prerequisites)

### Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/event-management-system.git
    cd event-management-system
    ```

2. **Configure the database**:
    - Create a MySQL database named `event_management_system`.
    - Import the .sql given in the db_sql folder in MySQL Workbench.
    - Update the `application.properties` file located in `src/main/resources` with your MySQL username and password.

3. **Build the project**:
    ```bash
    mvn clean install
    ```

4. **Run the application**:
    ```bash
    mvn spring-boot:run
    ```

5. **Access the application**:
    - The application will be running at `http://localhost:8080`.