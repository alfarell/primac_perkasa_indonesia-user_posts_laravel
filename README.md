# [PT Primac Perkasa Indonesia] Technical Test - BE Users and Posts API with Laravel

Author: Alfarell Muchamad Yuwanto

A simple RESTful API built with **Laravel Herd (Laravel 12, PHP 8.4)** that provides paginated users and their posts.  
The main endpoint `/api/users` returns users along with their associated posts using Eloquent relationships.

## Tech Stack

-   [Laravel 12](https://laravel.com/)
-   [PHP 8.4](https://www.php.net/)

## Features

-   CRUD API for **Users** and **Posts**
-   **One-to-Many relationship** (User → Posts)
-   **Pagination support** for `/api/users`

## Requirements

-   PHP 8.4
-   Composer 2.x
-   Laravel 12.x
-   Database SQLite

OR use

-   [Laravel Herd](https://herd.laravel.com/)

## Setup & Installation

Install dependencies

```bash
composer install
```

Create .env file

```bash
cp .env.example .env
```

Generate the app key

```bash
php artisan key:generate
```

Run migrations

```bash
php artisan migrate
```

Seed dummy data

```bash
php artisan db:seed
```

Run the Server

```bash
php artisan serve
```
