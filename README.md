# Grocery Store Management System   

Grocery Store Management System (GSMS) is a web application designed to manage products, orders, and other aspects of a grocery store. This system is built using Flask (a Python web framework) for the backend, HTML/CSS/JavaScript for the frontend, and MySQL for the database.

## Features

- **Manage Products:** Add, update, and delete products with details like name, unit, and price per unit.
- **View Orders:** Track and view customer orders with details such as date, order number, customer name, and total cost.
- **User-friendly Interface:** The application provides an intuitive and user-friendly interface for seamless navigation.

## Three-Tier Architecture

The three-tier architecture divides the application into three interconnected components, each responsible for specific functionalities. This design enhances modularity, maintainability, and scalability.

## 1. Frontend
The frontend is the user interface layer responsible for interacting with users and presenting data. In the case of GSMS, the frontend is implemented using HTML, CSS, and JavaScript.

## Components:

HTML: Defines the structure and layout of the web pages.
CSS: Styles the HTML elements for a visually appealing presentation.
JavaScript: Enhances interactivity, handles user input, and communicates with the backend.
Purpose:
Display product information, order details, and other user interfaces.
Send user requests to the backend for processing.

## 2. Backend

The backend is the logic layer that processes user requests, interacts with the database, and manages the application's business logic. GSMS uses Flask, a lightweight Python web framework, for the backend.

## Components:

Flask: Handles HTTP requests, routes, and provides a web server.
Python: Implements the application's logic, including CRUD (Create, Read, Update, Delete) operations.
Purpose:
Receive and process requests from the frontend.
Query the database for information.
Return data to the frontend for display.

## 3. Database

The database stores and manages the application's data. GSMS uses MySQL as the relational database management system.

Components:
MySQL: Manages the creation, retrieval, updating, and deletion of data.
SQL: Defines the structure of tables, relationships, and constraints.
Purpose:
Store information about products, orders, and other relevant data.
Enable data retrieval for the backend to respond to user requests.
