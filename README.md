# 🛍️ E-Commerce Web Application

🛒 Welcome to the Full Stack E-Commerce Website built with Angular, Java Spring Boot, and MySQL! 🚀

## Overview ℹ️
This repository contains the code for an E-commerce website. It's built using Angular for the front-end, Spring Boot for the back-end, and MySQL for the database. This project was created as part of the Full Stack Java and Spring Boot course to learn more about Full Stack Development.

## Features 🌟
-  **Product Listing**: View available products by category and see product details.
-  **Searching**: Search for products by keyword.
-  **Pagination**: Navigate through product listings with pagination.
-  **Shopping Cart**: Add, update, and remove products from your shopping cart.
-  **Checkout Form**: Fill out required fields to checkout and save orders.
-  **Login/Logout**: Secure authentication and authorization using Okta.
-  **Members-Only Pages**: Access routes only available to authenticated users.
-  **Handling Browser Refresh**: Store shopping cart data locally to prevent loss on refresh.
-  **Order History**: View order history with secure API access.

## Technologies Used 💻
- **Angular 16.2.1**: Front-end framework for single-page web applications.
- **TypeScript 5.1.6**: Adds static typing with optional type annotations to JavaScript.
- **Spring Boot 3.1.2**: Back-end framework for Java-based web applications.
- **Java 17.0.8**: Object-oriented programming language.
- **MySQL 8.0.17**: Relational database management system.
- **Okta 2.1.6**: Cloud-based identity and access management platform.

## Getting Started 🚀
### Prerequisites 🛠️
- **Node.js and npm**: Required for managing Angular dependencies.
- **Angular CLI**: Install globally for Angular application management.
- **Code Editor**: Choose from Visual Studio Code or IntelliJ.
- **Java Development Kit (JDK)**: Compatible with JDK 8, 11, or 16+.

### Installation 📥
1. Clone the repository: `git clone https://github.com/NesiCodes/Fullstack-Ecommerce-Web.git`
2. Navigate to the db-scripts directory: `cd 01-stater-files/db-scripts`
3. Execute each SQL script using MySql Workbench to create the database schema and tables.
4. Navigate to the back-end directory: `cd 02-backend/spring-boot rest api`
5. Open the project in IntelliJ IDE and let Maven automatically build and install dependencies.
6. Navigate to the front-end directory: `cd frontend/angular-ecommerce`
7. Install Angular CLI: `npm install -g @angular/cli`
8. Install front-end dependencies from package.json.

### Usage 🚀
1. Start the back-end server:
   - Navigate to the root of the project and execute `mvn spring-boot:run`.
   - Alternatively, run the `SpringBootEcommerceApplication` class in IntelliJ IDE.
2. Start the front-end development server:
   - Navigate to the root of the project and execute `ng serve`.
   - Alternatively, run the application in Webstorm IDE.
3. Access the application in a web browser at [http://localhost:4200](http://localhost:4200).

Happy shopping! 🛍️
