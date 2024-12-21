# Online Shopping Web Application

## Overview

This is an **Online Shopping Web Application** built using **Java Spring MVC**. It enables users to browse products, add them to a shopping cart, and complete secure transactions. The system features both user and admin functionalities, allowing users to manage their profiles and orders, while admins can manage products, users, and view orders. The goal is to create an efficient and seamless online shopping experience.

## Features

- **User Authentication**: Users can register, log in, and manage their accounts.
- **Product Catalog**: Browse and search for products across multiple categories.
- **Shopping Cart**: Add/remove products, view cart contents, and update quantities.
- **Order Management**: Users can place, view, and track their orders.
- **Admin Panel**: Admins can add, update, delete products, manage users, and view all orders.
- **Secure Payment Gateway**: Integration with a payment gateway to process transactions securely.

## Class Names

- `UserController`: Handles user authentication (login, registration, profile management).
- `ProductController`: Manages the display of products, adding to the cart, and placing orders.
- `AdminController`: Admin functionality for managing users, products, and orders.
- `OrderController`: Manages order creation, viewing order history, and tracking order status.

## Technologies Used

- **Java**: The programming language used to implement the business logic.
- **Spring MVC**: For creating the web application and handling HTTP requests.
- **Spring Security**: Manages authentication and authorization for users and admins.
- **Hibernate**: ORM for mapping the database to Java objects.
- **Thymeleaf**: Template engine used to render dynamic web pages.
- **Bootstrap**: Frontend framework for responsive and mobile-first design.
- **MySQL/PostgreSQL**: Database system used to store user, product, and order data.

## Requirements

- **Java 11 or above**.
- **Apache Maven**: For managing project dependencies.
- **MySQL or PostgreSQL**: You will need to configure your database according to the application’s requirements.

## Installation

### Steps to Run Locally

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/online-shopping-webapp.git
    cd online-shopping-webapp
    ```

2. **Configure the database**:
   - Edit the `application.properties` file in the `src/main/resources/` directory to configure the database connection settings:
   
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/online_shopping_db
   spring.datasource.username=root
   spring.datasource.password=your-password
   spring.jpa.hibernate.ddl-auto=update
3. **Install project dependencies**:
   ```bash
   mvn clean install
   ```
4. **Run the application**:
    ```bash
   mvn spring-boot:run
    ```
5. **Access the application**:
   ```bash
    http://localhost:8080
   ```
## Usage
Once the application is running, you can:

- For Users: Register, login, browse products, add items to the cart, and complete orders.
- For Admins: Manage the product catalog, manage user accounts, and view all orders.

## Contribution
Feel free to fork this repository and contribute by submitting pull requests or opening issues. If you have ideas for improvements or bug fixes, don't hesitate to contribute.

