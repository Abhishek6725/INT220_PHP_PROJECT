This e-commerce project aims to develop a robust and user-friendly online shopping platform using PHP for backend scripting and MySQL as the database. The primary goal of the project is to provide an efficient digital marketplace that allows users to browse, search, and purchase products seamlessly. The website will cater to a diverse audience by offering a range of products across multiple categories, with functionality that allows users to register, log in, manage their profiles, add products to a shopping cart, and complete purchases through a secure payment gateway

CREATE DATABASE your_database_name;

Installation
Clone the repository:

bash

git clone https://github.com/Abhishek6725/INT220_PHP_PROJECT

Navigate to the project directory:

bash

Install project dependencies:

bash
composer install
Set up your environment:

Copy .env.example to .env

bash
cp .env.example .env
Update the .env file with your database credentials and other configuration settings.
Create the database:

Log in to your MySQL server and create a database:
sql

CREATE DATABASE your_database_name;
Run database migrations (if applicable):

bash

php artisan migrate
(Replace php artisan migrate with the appropriate command for your framework or custom migration script.)

Start the development server:

bash

php -S localhost:8000
Usage
Access the application: Open your browser and navigate to http://localhost:8000.

Log in or create an account (if applicable).


