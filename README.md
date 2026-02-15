# Online Automotive Shop

A web-based platform for browsing and purchasing automotive parts, developed as a certification project.

## What it does

- Displays a catalog of car parts and accessories
- Manages user registration and secure login
- functionality for adding items to a shopping cart
- Simulates order processing and checkout
- Provides an admin interface for inventory management

## Tech Stack

- Frontend: HTML, CSS
- Backend: PHP
- Database: MySQL
- Server: Apache (via XAMPP/WAMP)

## Getting started

### Requirements

- XAMPP or WAMP server
- Web browser

### Setup

1. Clone the repository:
   git clone https://github.com/cati3000/Online-automotive-shop.git

2. Move the project files:
   Copy the `atestat_final` folder to your server's root directory (e.g., `C:\xampp\htdocs\`)

3. Database setup:
   - Open phpMyAdmin (http://localhost/phpmyadmin)
   - Create a new database
   - Import the SQL file found in the project folder (if available)

4. Configure connection:
   Update the database connection settings in the PHP config file to match your local credentials.

### Usage

Open your browser and navigate to:
http://localhost/atestat_final

## How it works

1. User browses categories to find specific auto parts
2. PHP scripts fetch product data dynamically from MySQL
3. Session management tracks logged-in users and cart contents
4. Forms collect shipping details for order finalization
5. Admin panel allows adding or editing products in the database

## Project structure

- atestat_final/ - Source code and web assets
- Documentație-atestat.docx - Project documentation and report
