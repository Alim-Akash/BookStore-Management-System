# 📚 Book Store Management System

🎥 **Demo Video**: [Watch on YouTube](https://youtu.be/TWcu89WPwJk)

A simple Laravel-based web application for managing bookstore inventory with full CRUD functionality. Built using Laravel 11, MySQL, and developed locally using Laravel Herd.

## 📝 Overview

This project allows you to manage a collection of books with the ability to:

- View all books in a paginated table
- Add new books with details: ID, Title, Author, Price, ISBN, Stock
- View full book details
- Update existing book entries
- Delete books with confirmation prompts

## ⚙️ Installation & Setup

### Prerequisites

- Laravel Herd (macOS) or Laravel installed via Composer
- PHP 8.3+
- MySQL

### Steps

```bash
# Clone the repository
git clone https://github.com/Alim-Akash/BookStore-Management-System.git
cd bookstore-management-system

# Install dependencies
composer install

# Copy environment file and generate key
cp .env.example .env
php artisan key:generate

# Update database credentials in .env
# DB_DATABASE=bookstore
# DB_USERNAME=root
# DB_PASSWORD=yourpassword

# Run migrations to create tables
php artisan migrate

# Serve the application
php artisan serve
```

If you're using Laravel Herd, your project will be automatically available at:

```
http://bookstore-management-system.test
```

Otherwise, visit:

```
http://localhost:8000
```

## 📂 Folder Structure

- `routes/web.php` – Route definitions
- `app/Http/Controllers/` – Controller logic
- `resources/views/` – Blade templates
- `database/migrations/` – Table definitions

## 📅 Project Info

- Course: Web Engineering Sessional
- Final Submission: 26 May, 2025

## 📄 License

This project is open-source and available under the MIT License.
