Simple Task Management System
--------------------------------------------------
A system that manages simple tasks

Overview
--------------------------------------------------
This system is developed using Laravel (version 9.25.1), ReactJS CRA with Typescript enabled and Context Approach. 
It is also made using bulma design framework with Responsive Web Design and SweetAlert2

Features
-------------------------------------------------
Create, Update/Edit and Deleting of Tasks
List of Tasks created

CLI Commands
-------------------------------------------------
### php artisan serve
Command will enable the application to run in php development server.
Navigate to browser and type [http://localhost:8080] or [http://127.0.0.1:8080]

### php artisan mysql:createdb tasks
Create a new mysql database schema based on the database config file

### php artisan migrate / php artisan migrate:fresh --seed
Command will create all required data tables for the system, with [:fresh --seed] it will create 100 dump data

### php artisan key:generate
Command to generate app key

### cp .env.example .env
Create a copy file of env.example

### npm install
This will install the required js modules to be used by the system

### npm run dev
Compiles the js files and it's necessary files to enable the full use of the system

### composer install
Installs the required PHP Library


System Requirements
-------------------------------------------------
Web Server
PHP 8.1.6
MySQL 8.1.6


How to isntall
-------------------------------------------------
Navigate to the web root directory and run the following commands
### composer install
### cp .env.example .env
### php artisan mysql:createdb tasks
### php artisan key:generate
### php artisan migrate / php artisan migrate:fresh --seed
### npm install
### npm run dev
### php artisan serve
