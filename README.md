# art_gallery_management_system
AGMSM - Exhibition & Product Management System

Description

AGMSM is a web-based application developed in PHP for managing exhibition events, products, and customer details. It provides an admin panel for managing key functionalities such as adding, deleting, and modifying exhibitions, products, and customer information.

Features

Admin Dashboard

Exhibition Event Management

Product Management

Customer Management

Feedback Handling

Secure Authentication

Installation

Prerequisites

PHP 7.x or higher

MySQL Database

Apache Server (XAMPP/WAMP recommended)

Setup Steps

Download and extract the project.

Place the agmsm folder in your web server's root directory (e.g., htdocs for XAMPP).

Import the provided SQL file (database.sql) into your MySQL database.

Update connection.php with your database credentials.

Start Apache and MySQL services.

Access the application via http://localhost/agmsm/

Folder Structure

agmsm/
│-- index.php             # Main entry point
│-- connection.php        # Database connection file
│-- admin/                # Admin panel files
│   │-- add_exhibitionevents.php
│   │-- add_product.php
│   │-- adminwelcome.php
│   │-- delete_*.php      # Various deletion scripts
│-- assets/               # CSS, JS, images (if any)
│-- database.sql          # Database schema

Usage

Admin Login: Access the admin panel and manage exhibitions and products.

Manage Events & Products: Add, modify, and delete entries as needed.

Customer Management: View and handle customer feedback and information.
