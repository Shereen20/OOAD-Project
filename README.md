# OOAD-Project
An MVC-based web application to streamline pharmacy operations — from stock and supplier management to billing and customer handling. Built with Spring Boot, Thymeleaf, and MySQL, this system ensures a user-friendly, secure, and efficient management experience.

🚀 Features
Stock Management: Auto-updating inventory with low-stock alerts.

Supplier Module: Tracks supplier details, purchase orders, and deliveries.

Customer Management: Maintains customer profiles and purchase history.

Billing System: Accurate invoices with multi-mode payment support.

User Roles: Role-based access (Admin, Sales, Inventory).

Dashboards: Visual stock analysis for informed decision-making.

🧠 Patterns & Principles
🔧 Architecture Pattern
Model–View–Controller (MVC):

Model: Java entities + JPA Repositories (e.g., Stock.java, StockRepository)

View: Thymeleaf templates (*.html)

Controller: REST endpoints (@Controller, @GetMapping, @PostMapping)

🧩 Design Patterns
Facade: CustomerFacade simplifies interaction with billing and customer modules.

Factory: UserFactory handles role-based user creation.

Adapter: BillAdapter bridges data formatting for admin view.

Singleton: Supplier ensures a single supplier instance.

📐 Design Principles
DIP: High-level modules depend on abstractions like CustomerFacade.

OCP: Billing logic is open to extensions (e.g., new payment methods).

SRP: Each class has a single responsibility (Customer.java, Bill.java, etc.).

ISP: Clean, focused interfaces like CustomerRepository, BillAdapter.
