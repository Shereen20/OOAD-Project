

# Pharmacy Management System

## Overview

This Pharmacy Management System is a comprehensive solution designed to streamline the operations of modern pharmacies. Built using the **Spring Boot MVC** architecture, this project integrates essential features like **Stock Management**, **Billing Management**, and **Supplier Management** to ensure efficient, accurate, and reliable management of pharmaceutical operations.

## Features

- **Stock Management:**
  - Real-time inventory tracking and management.
  - Automated alerts for low stock levels.
  - Detailed reporting on stock usage and availability.

- **Billing Management:**
  - Efficient and accurate billing processes.
  - Generation of invoices and receipts.
  - Integration with payment gateways for seamless transactions.

- **Supplier Management:**
  - Management of supplier information and contacts.
  - Streamlined ordering and reordering processes.
  - Tracking of supplier performance and delivery schedules.

## Technologies Used

- **Spring Boot** - Framework for building the application.
- **Spring MVC** - Architectural pattern for implementing the web application.
- **Thymeleaf** - Template engine for rendering views.
- **Hibernate** - ORM framework for database interaction.
- **MySQL** - Relational database for storing data.
- **Maven** - Build and dependency management tool.

## Patterns and Principles used:
**Patterns:**
1. Singleton
2. Factory
3. Facade
4. Adapter

**Principles:**
1. Single Responsibility
2. Open Closed
3. Interface Segregation
4. Dependency Inversion

## Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/OOAD-Project/Pharmacy-System-Management-main.git
   cd pharmacy-management-system
   ```

2. **Configure the database:**
   - Create a MySQL database named `pharmacy_db`.
   - Update the database configuration in `src/main/resources/application.properties`:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/pharmacy_db
     spring.datasource.username=your_username
     spring.datasource.password=your_password
     ```

3. **Build and run the project:**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

4. **Access the application:**
   - Open your web browser and go to `http://localhost:8080`.
  
## Usage

- **Admin Dashboard:**
  - Manage stock, billing, and supplier information from a single interface.
  - View detailed reports and analytics.

- **Pharmacy Staff:**
  - Process sales and manage billing.
  - Track and reorder stock.

