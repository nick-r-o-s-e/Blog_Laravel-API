# Laravel API

## Table of Contents

-   [About](#about)
-   [Getting Started](#getting-started)
-   [Key Features](#key-features)

## About

This porject is the backend of a blog management application, built with Laravel. It provides a RESTful API for managing blog posts and interacts with a MySQL database. The API follows best practices for validation, error handling, and database management, making it scalable and maintainable.

### Hosted React Front-end: https://

## Key Features

### RESTful API

-   CRUD operations for blog posts.
-   API request validation for security and data integrity.
-   Structured error handling for better debugging and API responses.

### Database & Migrations

-   MySQL database integration.
-   Migrations and seeders for quick setup and testing.

### Hosting & Deployment

-   The backend is hosted on [Railway](https://railway.com/) with a MySQL database.

## Getting Started

## Follow these steps to set up and run the project locally:

### Prerequisites

-   Ensure MySQL is running.
-   Install Node.js and npm.
-   Install Composer for managing PHP dependencies.

#### Clone the repository:

```
git clone https://github.com/nick-r-o-s-e/
```

#### Install PHP dependencies:

```
composer install
```

#### Set up the environment file:

-   Create a .env file in the back folder.
-   Add YOUR database connection settings (e.g., database name, username, and password).

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=blog_crud
DB_USERNAME=root
DB_PASSWORD=
```

#### Run database migrations:

```
php artisan migrate
```

#### Seed the database (optional):

```
php artisan db:seed
```

#### Start the server:

```
php artisan serve
```

The backend server usually will be available at http://127.0.0.1:8000
